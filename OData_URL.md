
```HTTP
http(s)://<Hostname>:<Service i.e Port Number>/(rest is from the relevant ICF path).
```

## How to know Hostname and Service name (Port Number)

1. Go to t-code `SICF`
2. Execute with default values (F8)
3. `Goto` -> `Port Information` => ==Information of the system==
4. Enter `ServiceName` & apply
5. Expend recursively the folders (default_host) <= ICF Path

URL => {HTTP} + {HOSTNAME} + {Service(Port Number)} + {ICF path}