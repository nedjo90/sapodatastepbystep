## Count the number of entries of a query

REQUEST:
```HTTP
{{baseurl}}POHeaderSet/$count
```

STATUS:
```HTTP
200OK
```

BODY:
```HTTP
10
```
=> The number of entries if we query:

```HTTP
{{baseurl}}POHeaderSet
```