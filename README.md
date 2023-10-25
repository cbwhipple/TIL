# TIL
Memos for capturing things I learned.



## Powershell


### Find process listening on port

To identify a process listening on a particular post, run the following command:
```ps
netstat -aon | findstr "PORT_NUMBER"
```
