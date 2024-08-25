## **Exemple of entry with navigation property**

Request:

```HTTP
{{baseurl}}POHeaderSet?$format=xml
```

STATUS:
```HTTP
200ok
```

BODY:
```XML
<feed xmlns="http://www.w3.org/2005/Atom" xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices" xml:base="{{baseurl}}">
    <id>{{baseurl}}POHeaderSet</id>
    <title type="text">POHeaderSet</title>
    <updated>2024-08-25T14:49:02Z</updated>
    <author>
        <name/>
    </author>
    <link href="POHeaderSet" rel="self" title="POHeaderSet"/>
    <entry>
        <id>{{baseurl}}POHeaderSet('4500000000')</id>
        <title type="text">POHeaderSet('4500000000')</title>
        <updated>2024-08-25T14:49:02Z</updated>
        <category term="{{service}}.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000000')" rel="self" title="POHeader"/>
        <link href="POHeaderSet('4500000000')/HeadToItemNav" rel="http://schemas.microsoft.com/ado/2007/08/dataservices/related/HeadToItemNav" type="application/atom+xml;type=feed" title="HeadToItemNav"/>
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
        <id>{{baseurl}}POHeaderSet('4500000001')</id>
        <title type="text">POHeaderSet('4500000001')</title>
        <updated>2024-08-25T14:49:02Z</updated>
        <category term="{{service}}.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000001')" rel="self" title="POHeader"/>
        <link href="POHeaderSet('4500000001')/HeadToItemNav" rel="http://schemas.microsoft.com/ado/2007/08/dataservices/related/HeadToItemNav" type="application/atom+xml;type=feed" title="HeadToItemNav"/>
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
        <id>{{baseurl}}POHeaderSet('4500000002')</id>
        <title type="text">POHeaderSet('4500000002')</title>
        <updated>2024-08-25T14:49:02Z</updated>
        <category term="{{service}}.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000002')" rel="self" title="POHeader"/>
        <link href="POHeaderSet('4500000002')/HeadToItemNav" rel="http://schemas.microsoft.com/ado/2007/08/dataservices/related/HeadToItemNav" type="application/atom+xml;type=feed" title="HeadToItemNav"/>
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
        <id>{{baseurl}}POHeaderSet('4500000003')</id>
        <title type="text">POHeaderSet('4500000003')</title>
        <updated>2024-08-25T14:49:02Z</updated>
        <category term="{{service}}.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000003')" rel="self" title="POHeader"/>
        <link href="POHeaderSet('4500000003')/HeadToItemNav" rel="http://schemas.microsoft.com/ado/2007/08/dataservices/related/HeadToItemNav" type="application/atom+xml;type=feed" title="HeadToItemNav"/>
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
        <id>{{baseurl}}POHeaderSet('4500000004')</id>
        <title type="text">POHeaderSet('4500000004')</title>
        <updated>2024-08-25T14:49:02Z</updated>
        <category term="{{service}}.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000004')" rel="self" title="POHeader"/>
        <link href="POHeaderSet('4500000004')/HeadToItemNav" rel="http://schemas.microsoft.com/ado/2007/08/dataservices/related/HeadToItemNav" type="application/atom+xml;type=feed" title="HeadToItemNav"/>
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
        <id>{{baseurl}}POHeaderSet('4500000005')</id>
        <title type="text">POHeaderSet('4500000005')</title>
        <updated>2024-08-25T14:49:02Z</updated>
        <category term="{{service}}.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000005')" rel="self" title="POHeader"/>
        <link href="POHeaderSet('4500000005')/HeadToItemNav" rel="http://schemas.microsoft.com/ado/2007/08/dataservices/related/HeadToItemNav" type="application/atom+xml;type=feed" title="HeadToItemNav"/>
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
        <id>{{baseurl}}POHeaderSet('4500000006')</id>
        <title type="text">POHeaderSet('4500000006')</title>
        <updated>2024-08-25T14:49:02Z</updated>
        <category term="{{service}}.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000006')" rel="self" title="POHeader"/>
        <link href="POHeaderSet('4500000006')/HeadToItemNav" rel="http://schemas.microsoft.com/ado/2007/08/dataservices/related/HeadToItemNav" type="application/atom+xml;type=feed" title="HeadToItemNav"/>
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
        <id>{{baseurl}}POHeaderSet('4500000007')</id>
        <title type="text">POHeaderSet('4500000007')</title>
        <updated>2024-08-25T14:49:02Z</updated>
        <category term="{{service}}.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000007')" rel="self" title="POHeader"/>
        <link href="POHeaderSet('4500000007')/HeadToItemNav" rel="http://schemas.microsoft.com/ado/2007/08/dataservices/related/HeadToItemNav" type="application/atom+xml;type=feed" title="HeadToItemNav"/>
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
        <id>{{baseurl}}POHeaderSet('4500000008')</id>
        <title type="text">POHeaderSet('4500000008')</title>
        <updated>2024-08-25T14:49:02Z</updated>
        <category term="{{service}}.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000008')" rel="self" title="POHeader"/>
        <link href="POHeaderSet('4500000008')/HeadToItemNav" rel="http://schemas.microsoft.com/ado/2007/08/dataservices/related/HeadToItemNav" type="application/atom+xml;type=feed" title="HeadToItemNav"/>
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
        <id>{{baseurl}}POHeaderSet('4500000009')</id>
        <title type="text">POHeaderSet('4500000009')</title>
        <updated>2024-08-25T14:49:02Z</updated>
        <category term="{{service}}.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POHeaderSet('4500000009')" rel="self" title="POHeader"/>
        <link href="POHeaderSet('4500000009')/HeadToItemNav" rel="http://schemas.microsoft.com/ado/2007/08/dataservices/related/HeadToItemNav" type="application/atom+xml;type=feed" title="HeadToItemNav"/>
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


## **Access to a new href link**

```XML
<link href="POHeaderSet('4500000000')/HeadToItemNav" rel="http://schemas.microsoft.com/ado/2007/08/dataservices/related/HeadToItemNav" type="application/atom+xml;type=feed" title="HeadToItemNav"/>
```

Give a hint for navigate to POItem data by adding the Navigation Property the Query option.

## **Test of Query option with Navigation Property**

Request:

```HTTP
{baseurl}POHeaderSet('4500000000')/HeadToItemNav
```

STATUS:
```HTTP
200ok
```

BODY:
```XML
<feed xmlns="http://www.w3.org/2005/Atom" xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices" xml:base="{baseurl}">
    <id>{baseurl}POHeaderSet('4500000000')/HeadToItemNav</id>
    <title type="text">POItemSet</title>
    <updated>2024-08-25T15:18:06Z</updated>
    <author>
        <name/>
    </author>
    <link href="POHeaderSet('4500000000')/HeadToItemNav" rel="self" title="POItemSet"/>
    <entry>
        <id>{baseurl}POItemSet(Ebeln='4500000000',Ebelp='00010')</id>
        <title type="text">POItemSet(Ebeln='4500000000',Ebelp='00010')</title>
        <updated>2024-08-25T15:18:06Z</updated>
        <category term="{service}.POItem" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
        <link href="POItemSet(Ebeln='4500000000',Ebelp='00010')" rel="self" title="POItem"/>
        <content type="application/xml">
            <m:properties xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
                <d:Ebeln>4500000000</d:Ebeln>
                <d:Ebelp>00010</d:Ebelp>
                <d:Loekz></d:Loekz>
                <d:Statu></d:Statu>
                <d:Txz01>Trad.Good 10,PD,Third Party</d:Txz01>
                <d:Matnr>TG10</d:Matnr>
                <d:Werks>2510</d:Werks>
                <d:Lgort></d:Lgort>
                <d:Ktmng>0.000</d:Ktmng>
                <d:Menge>1.000</d:Menge>
            </m:properties>
        </content>
    </entry>
</feed>
```

\<entry>\<id> give the alternative link to get the exact one POItem

## **Test of the navigation entry**

Request:

```HTTP
{{baseurl}}POItemSet(Ebeln='4500000000',Ebelp='00010')
```

STATUS:
```HTTP
200ok
```

BODY:
```XML
<?xml version="1.0" encoding="utf-8"?>
<entry xml:base="{baseurl}" xmlns="http://www.w3.org/2005/Atom" xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
    <id>{baseurl}POItemSet(Ebeln='4500000000',Ebelp='00010')</id>
    <title type="text">POItemSet(Ebeln='4500000000',Ebelp='00010')</title>
    <updated>2024-08-25T15:25:08Z</updated>
    <category term="{service}.POItem" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
    <link href="POItemSet(Ebeln='4500000000',Ebelp='00010')" rel="self" title="POItem"/>
    <content type="application/xml">
        <m:properties>
            <d:Ebeln>4500000000</d:Ebeln>
            <d:Ebelp>00010</d:Ebelp>
            <d:Loekz/>
            <d:Statu/>
            <d:Txz01>Trad.Good 10,PD,Third Party</d:Txz01>
            <d:Matnr>TG10</d:Matnr>
            <d:Werks>2510</d:Werks>
            <d:Lgort/>
            <d:Ktmng>0.000</d:Ktmng>
            <d:Menge>1.000</d:Menge>
        </m:properties>
    </content>
</entry>
```

You get the same data

## **Test with expand option**


Request:

```HTTP
{{baseurl}}POHeaderSet('4500000000')?$expand=HeadToItemNav
```

STATUS:
```HTTP
200ok
```

BODY:
```XML
<?xml version="1.0" encoding="utf-8"?>
<entry xml:base="{baseurl}" xmlns="http://www.w3.org/2005/Atom" xmlns:m="http://schemas.microsoft.com/ado/2007/08/dataservices/metadata" xmlns:d="http://schemas.microsoft.com/ado/2007/08/dataservices">
    <id>{baseurl}POHeaderSet('4500000000')</id>
    <title type="text">POHeaderSet('4500000000')</title>
    <updated>2024-08-25T15:27:32Z</updated>
    <category term="{service}.POHeader" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
    <link href="POHeaderSet('4500000000')" rel="self" title="POHeader"/>
    <link href="POHeaderSet('4500000000')/HeadToItemNav" rel="http://schemas.microsoft.com/ado/2007/08/dataservices/related/HeadToItemNav" type="application/atom+xml;type=feed" title="HeadToItemNav">
        <m:inline>
            <feed xml:base="{baseurl}">
                <id>{baseurl}POHeaderSet('4500000000')/HeadToItemNav</id>
                <title type="text">POItemSet</title>
                <updated>2024-08-25T15:27:32Z</updated>
                <author>
                    <name/>
                </author>
                <link href="POHeaderSet('4500000000')/HeadToItemNav" rel="self" title="POItemSet"/>
                <entry>
                    <id>{baseurl}POItemSet(Ebeln='4500000000',Ebelp='00010')</id>
                    <title type="text">POItemSet(Ebeln='4500000000',Ebelp='00010')</title>
                    <updated>2024-08-25T15:27:32Z</updated>
                    <category term="{service}.POItem" scheme="http://schemas.microsoft.com/ado/2007/08/dataservices/scheme"/>
                    <link href="POItemSet(Ebeln='4500000000',Ebelp='00010')" rel="self" title="POItem"/>
                    <content type="application/xml">
                        <m:properties>
                            <d:Ebeln>4500000000</d:Ebeln>
                            <d:Ebelp>00010</d:Ebelp>
                            <d:Loekz/>
                            <d:Statu/>
                            <d:Txz01>Trad.Good 10,PD,Third Party</d:Txz01>
                            <d:Matnr>TG10</d:Matnr>
                            <d:Werks>2510</d:Werks>
                            <d:Lgort/>
                            <d:Ktmng>0.000</d:Ktmng>
                            <d:Menge>1.000</d:Menge>
                        </m:properties>
                    </content>
                </entry>
            </feed>
        </m:inline>
    </link>
    <content type="application/xml">
        <m:properties>
            <d:Ebeln>4500000000</d:Ebeln>
            <d:Bukrs>2510</d:Bukrs>
            <d:Bstyp>F</d:Bstyp>
            <d:Bsart>NB</d:Bsart>
            <d:Loekz/>
            <d:Statu>9</d:Statu>
            <d:Ernam>JOHAI</d:Ernam>
            <d:Lifnr>25402510</d:Lifnr>
            <d:Zterm>0001</d:Zterm>
        </m:properties>
    </content>
</entry>
```

With expand you get the header level data:

```XML
 <content type="application/xml">
        <m:properties>
            <d:Ebeln>4500000000</d:Ebeln>
            <d:Bukrs>2510</d:Bukrs>
            <d:Bstyp>F</d:Bstyp>
            <d:Bsart>NB</d:Bsart>
            <d:Loekz/>
            <d:Statu>9</d:Statu>
            <d:Ernam>JOHAI</d:Ernam>
            <d:Lifnr>25402510</d:Lifnr>
            <d:Zterm>0001</d:Zterm>
        </m:properties>
    </content>
```