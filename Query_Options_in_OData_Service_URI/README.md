> `?` => Beginning of an option

> `&` => Add an other option

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
         10. 
2. READ one particular field or property of the Entity Type (/Field1)
   1. By Fieldname
      1. `URL = {basurl}{endpoint}('{parameter}')/{Fieldname}` (! CASE SENSITIVE !)
      2. Test it: [For example](./ABAP_POHEADERSET_GET_ENTITY_BY_FIELDNAME.md)
3. Count the number of entries in the system ($count)
   1. `URL = {basurl}{endpoint}/$count`
   2. Test it: [for example](./ABAP_POHEADERSET_COUNT.md)
4. Extract only some fields of the Entity Type ($select=Field1,Field2,Field3)
   1. `URL = {basurl}{endpoint}?$select=Field1,Field2,Field3` (! CASE SENSITIVE !)
   2. Test it: [for example](./ABAP_POHEADERSET_GET_ENTITY_SOME_FIELDS.md)
   3. In JSON:
      1. `URL = {basurl}{endpoint}?$select=Field1,Field2,Field3&$format=json`
5. [Understand importing parameter with IT_KEY_TAB](./Importing_parameter_with_IT_KEY_TAB.md)