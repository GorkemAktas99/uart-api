# UART Service for IoT Systems
This program helps to transfer data via UART
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
