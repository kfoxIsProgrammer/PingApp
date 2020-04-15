

# CloudFlare_PingApp

CloudFlare_PingApp is a CLI application that emulates the ping command.


## Usage

```
./pingApp Google.com
```
## Output
```
Resolving DNS..

Trying to connect to 'Google.com' IP: 172.217.13.174

Reverse Lookup domain: yul03s04-in-f14.1e100.net
Socket file descriptor 3 received

Socket set to TTL..
64 bytes from yul03s04-in-f14.1e100.net (h: Google.com) (172.217.13.174) msg_seq=1 ttl=64 rtt = 6.816629 ms.
64 bytes from yul03s04-in-f14.1e100.net (h: Google.com) (172.217.13.174) msg_seq=2 ttl=64 rtt = 6.195545 ms.
64 bytes from yul03s04-in-f14.1e100.net (h: Google.com) (172.217.13.174) msg_seq=3 ttl=64 rtt = 5.687518 ms.
^C64 bytes from yul03s04-in-f14.1e100.net (h: Google.com) (172.217.13.174) msg_seq=4 ttl=64 rtt = 6.756840 ms.

===172.217.13.174 ping statistics===

4 packets sent, 4 packets received, 0.000000 percent packet loss. Total time: 3527.162251 ms.

```



## License
This Application has been repurposed by Kevin Fox
Original: https://www.geeksforgeeks.org/ping-in-c/


>In Response to Cloudflare Internship Application: Systems
>>By:Kevin Fox


This application is emulate the ping function.


> Compile the C code using
```
gcc -o pingApp pingApp.c
```

> Example
```
sudo ./pingApp Google.com
```
To end the pings press ctrl + c
Diagnostics will then be displayed
