# UART Service for IoT Systems
This program helps to transfer data via UART</br>
Also it's using in Gooz Project for Gooz Client ( not yet released )
## How To Use
```shell
go run main.go
```
Then service run at 5000 port
## Send Data
To send data, have to be sent example JSON to localhost:5000/exec ( shortly /exec endpoint )
```json
{
    "comPort":"COM6",
    "cmd":"data"
}
```
## Receive Data
Actually this API received data automatically. If you send a data then you receive a data.
## Future Plans
- [ ] Managing Data
- [ ] Database connection
- [ ] Different data styles
