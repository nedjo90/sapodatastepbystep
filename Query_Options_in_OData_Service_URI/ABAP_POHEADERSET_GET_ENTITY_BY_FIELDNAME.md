## **Get by number and by fieldname**

```HTTP
{{baseurl}}POHeaderSet('4500000001')/Lifnr
```

Response:

STATUS:
```HTTP
200OK
```

BODY:

```XML
<?xml version="1.0" encoding="utf-8"?>
<d:Lifnr xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices" xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata">7K300010</d:Lifnr>
```

## with json format

```HTTP
{{baseurl}}POHeaderSet('4500000001')/Lifnr?$format=json
```

Response:

STATUS:
```HTTP
200OK
```

BODY:

```JSON
{
    "d": {
        "Lifnr": "7K300010"
    }
}
```