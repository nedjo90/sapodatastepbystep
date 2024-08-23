
Example of method to populate:

```ABAP
SELECT * UP TO 10 ROWS FROM ekko INTO CORRESPONDING FIELDS OF TABLE et_entityset.
```

Response:

```XML
<feed xmlns="http://www.w3.org/2005/Atom" xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices" xml:base="{baseurl}">
    <id>{baseurl}POHeaderSet</id>
    <title type="text">POHeaderSet</title>
    <updated>2024-08-23T09:44:26Z</updated>
    <author>
        <name/>
    </author>
    <link href="POHeaderSet" rel="self" title="POHeaderSet"/>
    <entry>
        <id>{baseurl}POHeaderSet('4500000000')</id>
        <title type="text">POHeaderSet('4500000000')</title>
        <updated>2024-08-23T09:44:26Z</updated>
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
        <updated>2024-08-23T09:44:26Z</updated>
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
        <updated>2024-08-23T09:44:26Z</updated>
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
        <updated>2024-08-23T09:44:26Z</updated>
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
        <updated>2024-08-23T09:44:26Z</updated>
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
        <updated>2024-08-23T09:44:26Z</updated>
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
        <updated>2024-08-23T09:44:26Z</updated>
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
        <updated>2024-08-23T09:44:26Z</updated>
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
        <updated>2024-08-23T09:44:26Z</updated>
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
        <updated>2024-08-23T09:44:26Z</updated>
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

Status:

```HTTP
=> 200OK
```

You could test win JSON:
```URL
{URL}?$format=json
```

Response:

```JSON
{
    "d": {
        "results": [
            {
                "__metadata": {
                    "id": "{baseurl}POHeaderSet('4500000000')",
                    "uri": "{baseurl}POHeaderSet('4500000000')",
                    "type": "ZGW_SECOND_PO_NEHAN_SRV.POHeader"
                },
                "Ebeln": "4500000000",
                "Bukrs": "2510",
                "Bstyp": "F",
                "Bsart": "NB",
                "Loekz": "",
                "Statu": "9",
                "Ernam": "JOHAI",
                "Lifnr": "25402510",
                "Zterm": "0001"
            },
            {
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
            },
            {
                "__metadata": {
                    "id": "{baseurl}POHeaderSet('4500000002')",
                    "uri": "{baseurl}POHeaderSet('4500000002')",
                    "type": "ZGW_SECOND_PO_NEHAN_SRV.POHeader"
                },
                "Ebeln": "4500000002",
                "Bukrs": "7K10",
                "Bstyp": "F",
                "Bsart": "NB",
                "Loekz": "",
                "Statu": "9",
                "Ernam": "DOFAS",
                "Lifnr": "7K300002",
                "Zterm": "0004"
            },
            {
                "__metadata": {
                    "id": "{baseurl}POHeaderSet('4500000003')",
                    "uri": "{baseurl}POHeaderSet('4500000003')",
                    "type": "ZGW_SECOND_PO_NEHAN_SRV.POHeader"
                },
                "Ebeln": "4500000003",
                "Bukrs": "7K10",
                "Bstyp": "F",
                "Bsart": "NB",
                "Loekz": "",
                "Statu": "",
                "Ernam": "CEROY",
                "Lifnr": "7K300003",
                "Zterm": "0004"
            },
            {
                "__metadata": {
                    "id": "{baseurl}POHeaderSet('4500000004')",
                    "uri": "{baseurl}POHeaderSet('4500000004')",
                    "type": "ZGW_SECOND_PO_NEHAN_SRV.POHeader"
                },
                "Ebeln": "4500000004",
                "Bukrs": "7K10",
                "Bstyp": "F",
                "Bsart": "NB",
                "Loekz": "",
                "Statu": "9",
                "Ernam": "ARRIC",
                "Lifnr": "7K300001",
                "Zterm": "0004"
            },
            {
                "__metadata": {
                    "id": "{baseurl}POHeaderSet('4500000005')",
                    "uri": "{baseurl}POHeaderSet('4500000005')",
                    "type": "ZGW_SECOND_PO_NEHAN_SRV.POHeader"
                },
                "Ebeln": "4500000005",
                "Bukrs": "1010",
                "Bstyp": "F",
                "Bsart": "NB",
                "Loekz": "",
                "Statu": "9",
                "Ernam": "LOJEU",
                "Lifnr": "",
                "Zterm": ""
            },
            {
                "__metadata": {
                    "id": "{baseurl}POHeaderSet('4500000006')",
                    "uri": "{baseurl}POHeaderSet('4500000006')",
                    "type": "ZGW_SECOND_PO_NEHAN_SRV.POHeader"
                },
                "Ebeln": "4500000006",
                "Bukrs": "1010",
                "Bstyp": "F",
                "Bsart": "NB",
                "Loekz": "",
                "Statu": "9",
                "Ernam": "LOJEU",
                "Lifnr": "",
                "Zterm": ""
            },
            {
                "__metadata": {
                    "id": "{baseurl}POHeaderSet('4500000007')",
                    "uri": "{baseurl}POHeaderSet('4500000007')",
                    "type": "ZGW_SECOND_PO_NEHAN_SRV.POHeader"
                },
                "Ebeln": "4500000007",
                "Bukrs": "1010",
                "Bstyp": "F",
                "Bsart": "NB",
                "Loekz": "",
                "Statu": "9",
                "Ernam": "LOJEU",
                "Lifnr": "",
                "Zterm": ""
            },
            {
                "__metadata": {
                    "id": "{baseurl}POHeaderSet('4500000008')",
                    "uri": "{baseurl}POHeaderSet('4500000008')",
                    "type": "ZGW_SECOND_PO_NEHAN_SRV.POHeader"
                },
                "Ebeln": "4500000008",
                "Bukrs": "1010",
                "Bstyp": "F",
                "Bsart": "NB",
                "Loekz": "",
                "Statu": "9",
                "Ernam": "LOJEU",
                "Lifnr": "",
                "Zterm": ""
            },
            {
                "__metadata": {
                    "id": "{baseurl}POHeaderSet('4500000009')",
                    "uri": "{baseurl}POHeaderSet('4500000009')",
                    "type": "ZGW_SECOND_PO_NEHAN_SRV.POHeader"
                },
                "Ebeln": "4500000009",
                "Bukrs": "7K10",
                "Bstyp": "F",
                "Bsart": "NB",
                "Loekz": "",
                "Statu": "9",
                "Ernam": "ADBUT",
                "Lifnr": "7K300003",
                "Zterm": "0004"
            }
        ]
    }
}
```

