##User profiles
```
netsh wlan show profiles
```
## see views
```
netsh wlan show profile "profile name" key=clear
```
## Finding PID of Port No

```
netstat -ano | findstr :<PORT>
```
```
netstat -ano | findstr :8081
```
> Killing the PID of the PORT
```
taskkill /PID <process ID> /F
```
