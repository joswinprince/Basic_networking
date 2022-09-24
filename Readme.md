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
> Killing the PID of the PORT
```
taskkill /PID <process ID> /F
```
