# Pymodbus Example

> This is a working example of pymodbus from the example folder.

## Requirements
Python3+

## Installation
```bash 
pip install -r requirements.txt
```

## Usage.
```bash 
python server_sync.py [-h] [--comm {tcp,udp,serial,tls}]
                   [--framer {ascii,rtu,socket,tls}]
                   [--log {critical,error,warning,info,debug}]
                   [--port PORT] [--store {sequential,sparse,factory,none}]
                   [--slaves SLAVES]
```

### Example
```bash
python server_sync.py  -c tcp -l debug -p 502 --slaves 1 --store sequential --framer socket ```     