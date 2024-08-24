1. READ Operation (i.e. GET ENTITY method)
   1. `GET` only `PO numbers` details (i.e 4500000001)
      1. Implement the method
         1. Go to `SEGW`
         2. Right-click on {service}/Service Implementation/POHeaderSet/GetEntity (Read)
         3. `Go to ABAP Workbench`
         4. Select `POHEADERSET_GET_ENTITY`
         5. Right-click on `Redefine`
         6. Enter your logic in the method 
         7. Test it with postman, sap client or browser
            1. `URL = {basurl}{endpoint}('{parameter}')`
         8. Test in JSON
            1. 1. `URL = {basurl}{endpoint}('{parameter}')?$format=json`
         9.  See [For example](./ABAP_POHEADERSET_GET_ENTITY.md)
        