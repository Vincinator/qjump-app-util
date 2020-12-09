# qjump-app-util
QJump Application Utility

This tool is used to modify the socket options of binaries so that they can be used directly with QJump. 

## Build
Requirements: ```apt install libc6-dev```
To complie run ```make``` in the source directory. 

## Example
To use, run the qjau.py utility aginast the program you want to alter eg:  

```bash 
sudo ./qjau.py --window=9999999 --priority=5 --verbosity=2 --command="ping 127.0.0.1"
``` 

