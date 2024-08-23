# Define Data Model

1. **T-CODE** `SEGW`
2. **Create Project:**
   1. `Project` = `ZGW_MYPROJECT_PO_USERNAME`
   2. `Description` = `Service for PO`
   3. Click `Local Object` => Project created with 4 folders:
      1. **Data Model:**
         - **Entity Types**: Structure (work area = one row)
         - **Entity Set**: Internal table (more than one entity/rows)
      2. **Service Implementation**
      3. **Runtime Artifacts**
      4. **Service Maintenance**
   4. **Create structure with its internal table:**
      1. **With fields One By One:**
         - Right-click on `Entity Types` -> `Create`
         - Enter `Entity Type Name` = `POHeader` (Structure)
         - Check `Create Related Entity Set`
         - `Entity Set Name` = `POHeaderSet` (Internal Table) ![SEGW4](images/SEGW4.jpg)
         - Operations or Methods => triggered by endpoints
         - Define fields of the structure (work area) and internal table:
            - Double-click on `/Data Model/Entity Types/POHeader/Properties`
            - Create field:
               - Add field name
               - Add Type in `Edm Core Type`
               - Add Length in `Max`
            - Complete other configurations if needed
      2. **With fields using DDIC Structure:**
         - Right-click on `/Data Model` -> `Import` -> `DDIC Structure`
         - `Name` = `POHeader` (Structure)
         - Check `Entity Type`
         - `ABAP Structure` = `EKKO` (i.e.)
         - Check `Create Default Entity Set` (Create default relative internal table)
         - Hit `Next`
         - Select the desired fields
         - Hit `Next`
         - Select the `Is Key`
         - Hit `Finish`

# Implement / Register the Service

1. Hit ![Generate Runtime Object](images/Generate_Runtime_Object.png) (Generate Runtime Object) => Generation of the class for the:
   - **MPC (Model Provider Class)** => define the Gateway Service interface
   - **DPC (Data Provider Class)** => provides the Gateway Service functionalities
   - MPC & DPC are not connected by any coding => talk via Configuration
   - **Service Registration** => Technical Service which the external system needs to call
2. Provide Package and Transport
3. Save (i.e. local storage)

# Add Service to Service Catalog (Register the Service to Gateway Hub)

1. **Deployment:**
   1. **Embedded Deployment:**
      1. Click on `/Service Maintenance/{name of the service}`
      2. Select the system to activate
      3. Click on Register
      4. `System Alias` = `LOCAL` (i.e)
      5. `Creation Information -> Package Assignment` = `Local Object` (i.e)
      6. Hit on ![Validate](images/Validate.png)
   2. **Non-Embedded Deployment:**
      1. To complete

2. **Test the Service:**
   1. Click on `Maintain` (t-code: `/n/IWFND/MAINT_SERVICE`) and `Yes`
   2. Click on the service to test
   3. Click on `Call Browser` or `SAP Gateway Client` (t-code: `/n/IWFND/GW_CLIENT`)
      1. In `SAP Gateway Client`, click on `HTTP` to see the URL
         - => **CASE SENSITIVE**
   4. Test `{URL}?$format=xml`: ![[format=xml]](format_xml)
   5. Test `{URL}?$format=json`: ![[format=json]](images/format_json.png)
   6. Test `{URL}$metadata`: ![[metadata]](images/metadata.png)
   7. To see errors, use the service `/n/IWFND/ERROR_LOG`

# Pulling Data

1. `{URL}POHeaderSet` (internal table): ![[Get before method implementation]](images/Get_before_method_implementation.png)
2. **Implement Method:**
   1. Go to `SEGW`
   2. Right-click on `Service Implementation/{POHeaderSet}`
   3. Click on `Go to ABAP Workbench` & ![Validate](images/Validate.png)
   4. Right-click on `{project_name_DPC_EXT}/Methods/Inherited Methods/{service}_GET_ENTITYSET` & `Redefine`
   5. Save & Activate (F3)
   6. Test again the query `{URL}POHeaderSet` (internal table): ![[Get after method implementation]](images/Get_after_method_implementation.png)
   7. Enter a method to pull data
   8. Save & Activate
   9. Test again the query `{URL}POHeaderSet` (internal table): ![[Get after method implementation and populate table]](images/Get_after_method_implementation_and_populate_table.png)
   10. Understand OData URL ![[OData URL]](images/OData_URL.png)
