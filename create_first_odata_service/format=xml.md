
Response like:


```XML
<?xml version="1.0" encoding="utf-8"?>

<app:service xml:lang="en" xml:base="{baseurl}" xmlns:app="http://www.w3.org/2007/app" xmlns:atom="http://www.w3.org/2005/Atom" xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:sap="http://www.sap.com/Protocols/SAPData">

<app:workspace>

<atom:title type="text">Data</atom:title>

<app:collection sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:pageable="false" sap:content-version="1" href="POHeaderSet">

<atom:title type="text">POHeaderSet</atom:title>

<sap:member-title>POHeader</sap:member-title>

</app:collection>

<app:collection sap:creatable="false" sap:updatable="false" sap:deletable="false" sap:pageable="false" sap:content-version="1" href="POItemSet">

<atom:title type="text">POItemSet</atom:title>

<sap:member-title>POItem</sap:member-title>

</app:collection>

</app:workspace>

<atom:link rel="self" href="{baseurl}"/>

<atom:link rel="latest-version" href="{baseurl}"/>

</app:service>
```