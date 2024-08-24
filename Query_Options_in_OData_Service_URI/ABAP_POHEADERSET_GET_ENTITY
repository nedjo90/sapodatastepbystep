## **Example of Logique**:

```ABAP
DATA : ls_key_tab LIKE LINE OF it_key_tab,
lv_ebeln TYPE ekko-ebeln.

* IT_KEY_TAB has key name and value
READ TABLE it_key_tab INTO ls_key_tab
WITH KEY name = 'Ebeln'. " Case sensitive
IF sy-subrc EQ 0.
lv_ebeln = ls_key_tab-value.
ENDIF.

* Select one PO entry
SELECT SINGLE * FROM ekko INTO CORRESPONDING FIELDS OF er_entity
WHERE ebeln = lv_ebeln.
```

## **URI to test**:

```HTTP
 {{baseurl}}POHeaderSet('4500000001')
```

### **Response**

STATUS:
```HTTP
200OK
```

BODY:
```XML
<?xml version="1.0" encoding="utf-8"?>
<entry xml:base="{baseurl}" xmlns="http://www.w3.org/2005/Atom" xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
    <id>{baseurl}POHeaderSet('4500000001')</id>
    <title type="text">POHeaderSet('4500000001')</title>
    <updated>2024-08-24T10:31:56Z</updated>
    <category term="ZGW_SECOND_PO_NEHAN_SRV.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
    <link href="POHeaderSet('4500000001')" rel="self" title="POHeader"/>
    <content type="application/xml">
        <m:properties>
            <d:Ebeln>4500000001</d:Ebeln>
            <d:Bukrs>7K10</d:Bukrs>
            <d:Bstyp>F</d:Bstyp>
            <d:Bsart>NB</d:Bsart>
            <d:Loekz/>
            <d:Statu>9</d:Statu>
            <d:Ernam>DOFAS</d:Ernam>
            <d:Lifnr>7K300010</d:Lifnr>
            <d:Zterm>0004</d:Zterm>
        </m:properties>
    </content>
</entry>
```


## **Test with format in json**

## **URI to test**:

```HTTP
 {{baseurl}}POHeaderSet('4500000001')?$format=json
```

### **Response**

STATUS:
```HTTP
200OK
```

BODY:
```JSON
{
    "d": {
        "__metadata": {
            "id": "{baseurl}POHeaderSet('4500000001')",
            "uri": "{baseurl}POHeaderSet('4500000001')",
            "type": "ZGW_SECOND_PO_NEHAN_SRV.POHeader"
        },
        "Ebeln": "4500000001",
        "Bukrs": "7K10",
        "Bstyp": "F",
        "Bsart": "NB",
        "Loekz": "",
        "Statu": "9",
        "Ernam": "DOFAS",
        "Lifnr": "7K300010",
        "Zterm": "0004"
    }
}
```

## **See the URI for every number**

Request:

```HTTP
{{baseurl}}POHeaderSet
```

Response:

STATUS:
```HTTP
200OK
```

BODY:
```XML
<feed xmlns="http://www.w3.org/2005/Atom" xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices" xml:base="{baseurl}">
    <id>{baseurl}POHeaderSet</id>
    <title type="text">POHeaderSet</title>
    <updated>2024-08-24T10:48:37Z</updated>
    <author>
        <name/>
    </author>
    <link href="POHeaderSet" rel="self" title="POHeaderSet"/>
    <entry>
        <id>{baseurl}POHeaderSet('4500000000')</id>
        <title type="text">POHeaderSet('4500000000')</title>
        <updated>2024-08-24T10:48:37Z</updated>
        <category term="ZGW_SECOND_PO_NEHAN_SRV.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000000')" rel="self" title="POHeader"/>
        <content type="application/xml">
            <m:properties xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
                <d:Ebeln>4500000000</d:Ebeln>
                <d:Bukrs>2510</d:Bukrs>
                <d:Bstyp>F</d:Bstyp>
                <d:Bsart>NB</d:Bsart>
                <d:Loekz></d:Loekz>
                <d:Statu>9</d:Statu>
                <d:Ernam>JOHAI</d:Ernam>
                <d:Lifnr>25402510</d:Lifnr>
                <d:Zterm>0001</d:Zterm>
            </m:properties>
        </content>
    </entry>
    <entry>
        <id>{baseurl}POHeaderSet('4500000001')</id>
        <title type="text">POHeaderSet('4500000001')</title>
        <updated>2024-08-24T10:48:37Z</updated>
        <category term="ZGW_SECOND_PO_NEHAN_SRV.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000001')" rel="self" title="POHeader"/>
        <content type="application/xml">
            <m:properties xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
                <d:Ebeln>4500000001</d:Ebeln>
                <d:Bukrs>7K10</d:Bukrs>
                <d:Bstyp>F</d:Bstyp>
                <d:Bsart>NB</d:Bsart>
                <d:Loekz></d:Loekz>
                <d:Statu>9</d:Statu>
                <d:Ernam>DOFAS</d:Ernam>
                <d:Lifnr>7K300010</d:Lifnr>
                <d:Zterm>0004</d:Zterm>
            </m:properties>
        </content>
    </entry>
    <entry>
        <id>{baseurl}POHeaderSet('4500000002')</id>
        <title type="text">POHeaderSet('4500000002')</title>
        <updated>2024-08-24T10:48:37Z</updated>
        <category term="ZGW_SECOND_PO_NEHAN_SRV.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000002')" rel="self" title="POHeader"/>
        <content type="application/xml">
            <m:properties xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
                <d:Ebeln>4500000002</d:Ebeln>
                <d:Bukrs>7K10</d:Bukrs>
                <d:Bstyp>F</d:Bstyp>
                <d:Bsart>NB</d:Bsart>
                <d:Loekz></d:Loekz>
                <d:Statu>9</d:Statu>
                <d:Ernam>DOFAS</d:Ernam>
                <d:Lifnr>7K300002</d:Lifnr>
                <d:Zterm>0004</d:Zterm>
            </m:properties>
        </content>
    </entry>
    <entry>
        <id>{baseurl}POHeaderSet('4500000003')</id>
        <title type="text">POHeaderSet('4500000003')</title>
        <updated>2024-08-24T10:48:37Z</updated>
        <category term="ZGW_SECOND_PO_NEHAN_SRV.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000003')" rel="self" title="POHeader"/>
        <content type="application/xml">
            <m:properties xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
                <d:Ebeln>4500000003</d:Ebeln>
                <d:Bukrs>7K10</d:Bukrs>
                <d:Bstyp>F</d:Bstyp>
                <d:Bsart>NB</d:Bsart>
                <d:Loekz></d:Loekz>
                <d:Statu></d:Statu>
                <d:Ernam>CEROY</d:Ernam>
                <d:Lifnr>7K300003</d:Lifnr>
                <d:Zterm>0004</d:Zterm>
            </m:properties>
        </content>
    </entry>
    <entry>
        <id>{baseurl}POHeaderSet('4500000004')</id>
        <title type="text">POHeaderSet('4500000004')</title>
        <updated>2024-08-24T10:48:37Z</updated>
        <category term="ZGW_SECOND_PO_NEHAN_SRV.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000004')" rel="self" title="POHeader"/>
        <content type="application/xml">
            <m:properties xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
                <d:Ebeln>4500000004</d:Ebeln>
                <d:Bukrs>7K10</d:Bukrs>
                <d:Bstyp>F</d:Bstyp>
                <d:Bsart>NB</d:Bsart>
                <d:Loekz></d:Loekz>
                <d:Statu>9</d:Statu>
                <d:Ernam>ARRIC</d:Ernam>
                <d:Lifnr>7K300001</d:Lifnr>
                <d:Zterm>0004</d:Zterm>
            </m:properties>
        </content>
    </entry>
    <entry>
        <id>{baseurl}POHeaderSet('4500000005')</id>
        <title type="text">POHeaderSet('4500000005')</title>
        <updated>2024-08-24T10:48:37Z</updated>
        <category term="ZGW_SECOND_PO_NEHAN_SRV.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000005')" rel="self" title="POHeader"/>
        <content type="application/xml">
            <m:properties xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
                <d:Ebeln>4500000005</d:Ebeln>
                <d:Bukrs>1010</d:Bukrs>
                <d:Bstyp>F</d:Bstyp>
                <d:Bsart>NB</d:Bsart>
                <d:Loekz></d:Loekz>
                <d:Statu>9</d:Statu>
                <d:Ernam>LOJEU</d:Ernam>
                <d:Lifnr></d:Lifnr>
                <d:Zterm></d:Zterm>
            </m:properties>
        </content>
    </entry>
    <entry>
        <id>{baseurl}POHeaderSet('4500000006')</id>
        <title type="text">POHeaderSet('4500000006')</title>
        <updated>2024-08-24T10:48:37Z</updated>
        <category term="ZGW_SECOND_PO_NEHAN_SRV.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000006')" rel="self" title="POHeader"/>
        <content type="application/xml">
            <m:properties xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
                <d:Ebeln>4500000006</d:Ebeln>
                <d:Bukrs>1010</d:Bukrs>
                <d:Bstyp>F</d:Bstyp>
                <d:Bsart>NB</d:Bsart>
                <d:Loekz></d:Loekz>
                <d:Statu>9</d:Statu>
                <d:Ernam>LOJEU</d:Ernam>
                <d:Lifnr></d:Lifnr>
                <d:Zterm></d:Zterm>
            </m:properties>
        </content>
    </entry>
    <entry>
        <id>{baseurl}POHeaderSet('4500000007')</id>
        <title type="text">POHeaderSet('4500000007')</title>
        <updated>2024-08-24T10:48:37Z</updated>
        <category term="ZGW_SECOND_PO_NEHAN_SRV.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000007')" rel="self" title="POHeader"/>
        <content type="application/xml">
            <m:properties xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
                <d:Ebeln>4500000007</d:Ebeln>
                <d:Bukrs>1010</d:Bukrs>
                <d:Bstyp>F</d:Bstyp>
                <d:Bsart>NB</d:Bsart>
                <d:Loekz></d:Loekz>
                <d:Statu>9</d:Statu>
                <d:Ernam>LOJEU</d:Ernam>
                <d:Lifnr></d:Lifnr>
                <d:Zterm></d:Zterm>
            </m:properties>
        </content>
    </entry>
    <entry>
        <id>{baseurl}POHeaderSet('4500000008')</id>
        <title type="text">POHeaderSet('4500000008')</title>
        <updated>2024-08-24T10:48:37Z</updated>
        <category term="ZGW_SECOND_PO_NEHAN_SRV.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000008')" rel="self" title="POHeader"/>
        <content type="application/xml">
            <m:properties xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
                <d:Ebeln>4500000008</d:Ebeln>
                <d:Bukrs>1010</d:Bukrs>
                <d:Bstyp>F</d:Bstyp>
                <d:Bsart>NB</d:Bsart>
                <d:Loekz></d:Loekz>
                <d:Statu>9</d:Statu>
                <d:Ernam>LOJEU</d:Ernam>
                <d:Lifnr></d:Lifnr>
                <d:Zterm></d:Zterm>
            </m:properties>
        </content>
    </entry>
    <entry>
        <id>{baseurl}POHeaderSet('4500000009')</id>
        <title type="text">POHeaderSet('4500000009')</title>
        <updated>2024-08-24T10:48:37Z</updated>
        <category term="ZGW_SECOND_PO_NEHAN_SRV.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000009')" rel="self" title="POHeader"/>
        <content type="application/xml">
            <m:properties xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
                <d:Ebeln>4500000009</d:Ebeln>
                <d:Bukrs>7K10</d:Bukrs>
                <d:Bstyp>F</d:Bstyp>
                <d:Bsart>NB</d:Bsart>
                <d:Loekz></d:Loekz>
                <d:Statu>9</d:Statu>
                <d:Ernam>ADBUT</d:Ernam>
                <d:Lifnr>7K300003</d:Lifnr>
                <d:Zterm>0004</d:Zterm>
            </m:properties>
        </content>
    </entry>
</feed>
```

The id of each entry represent the uri to get the number detail:

```XML
 <id>{baseurl}POHeaderSet('4500000009')</id>
```