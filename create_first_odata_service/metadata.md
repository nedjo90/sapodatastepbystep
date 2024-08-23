
Response like:

```XML
<?xml version="1.0" encoding="utf-8"?>
<edmx:Edmx Version="1.0" xmlns:edmx="http://schemas.microsoft.com/ado/2007/06/edmx" xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:sap="http://www.sap.com/Protocols/SAPData">
    <edmx:DataServices m:DataServiceVersion="2.0">
        <Schema Namespace="ZGW_SECOND_PO_NEHAN_SRV" xml:lang="en" sap:schema-version="1" xmlns="http://schemas.microsoft.com/ado/2008/09/edm">
            <EntityType Name="POHeader" sap:content-version="1">
                <Key>
                    <PropertyRef Name="Ebeln"/>
                </Key>
                <Property Name="Ebeln" Type="Edm.String" Nullable="false" MaxLength="10" sap:unicode="false" sap:label="Purchasing Doc." sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Bukrs" Type="Edm.String" Nullable="false" MaxLength="4" sap:unicode="false" sap:label="Company Code" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Bstyp" Type="Edm.String" Nullable="false" MaxLength="1" sap:unicode="false" sap:label="Doc. Category" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Bsart" Type="Edm.String" Nullable="false" MaxLength="4" sap:unicode="false" sap:label="Document Type" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Loekz" Type="Edm.String" Nullable="false" MaxLength="1" sap:unicode="false" sap:label="Del. Indicator" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Statu" Type="Edm.String" Nullable="false" MaxLength="1" sap:unicode="false" sap:label="Status" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Ernam" Type="Edm.String" Nullable="false" MaxLength="12" sap:unicode="false" sap:label="Created By" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Lifnr" Type="Edm.String" Nullable="false" MaxLength="10" sap:unicode="false" sap:label="Supplier" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Zterm" Type="Edm.String" Nullable="false" MaxLength="4" sap:unicode="false" sap:label="Pyt Terms" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
            </EntityType>
            <EntityType Name="POItem" sap:content-version="1">
                <Key>
                    <PropertyRef Name="Ebeln"/>
                </Key>
                <Property Name="Ebeln" Type="Edm.String" Nullable="false" MaxLength="10" sap:unicode="false" sap:label="Purchasing Doc." sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Ebelp" Type="Edm.String" Nullable="false" MaxLength="5" sap:unicode="false" sap:label="Item" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Loekz" Type="Edm.String" Nullable="false" MaxLength="1" sap:unicode="false" sap:label="Del. Indicator" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Statu" Type="Edm.String" Nullable="false" MaxLength="1" sap:unicode="false" sap:label="Origin" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Txz01" Type="Edm.String" Nullable="false" MaxLength="40" sap:unicode="false" sap:label="Short Text" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Matnr" Type="Edm.String" Nullable="false" MaxLength="40" sap:unicode="false" sap:label="Material" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Werks" Type="Edm.String" Nullable="false" MaxLength="4" sap:unicode="false" sap:label="Plant" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Lgort" Type="Edm.String" Nullable="false" MaxLength="4" sap:unicode="false" sap:label="Location" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Ktmng" Type="Edm.Decimal" Nullable="false" Precision="13" Scale="3" sap:unicode="false" sap:label="Target Quantity" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
                <Property Name="Menge" Type="Edm.Decimal" Nullable="false" Precision="13" Scale="3" sap:unicode="false" sap:label="PO Quantity" sap:creatable="false" sap:updatable="false" sap:sortable="false" sap:filterable="false"/>
            </EntityType>
            <EntityContainer Name="ZGW_SECOND_PO_NEHAN_SRV_Entities" m:IsDefaultEntityContainer="true" sap:supported-formats="atom json xlsx">
                <EntitySet Name="POHeaderSet" EntityType="ZGW_SECOND_PO_NEHAN_SRV.POHeader" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:pageable="false" sap:content-version="1"/>
                <EntitySet Name="POItemSet" EntityType="ZGW_SECOND_PO_NEHAN_SRV.POItem" sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:pageable="false" sap:content-version="1"/>
            </EntityContainer>
            <Annotation Term="Core.SchemaVersion" String="1.0.0" xmlns="http://docs.oasis-open.org/odata/ns/edm"/>
            <atom:link rel="self" href="http://s4h.net-portail.com:8000/sap/opu/odata/sap/ZGW_SECOND_PO_NEHAN_SRV/$metadata" xmlns:atom="http://www.w3.org/2005/Atom"/>
            <atom:link rel="latest-version" href="http://s4h.net-portail.com:8000/sap/opu/odata/sap/ZGW_SECOND_PO_NEHAN_SRV/$metadata" xmlns:atom="http://www.w3.org/2005/Atom"/>
        </Schema>
    </edmx:DataServices>
</edmx:Edmx>
```