## obgswebperf
###Chapter 1. What Is Web Performance?
####Scope
###Chapter 3. T1 - The Connection Time
####Introduction to T1 - The Connection Time
The T1 time segment is defined as the time required to establish a TCP (or TLS)
connection to the server to which the HTTP request will be sent, and from which the (initial) response will be received.  

All of the T1 time occurs before the first HTTP request is even sent.  
The entire T1 sequence occurs at the network level, and no HTTP request is actually sent until the beginning of T2.  
####DNS: Internet Names and Addresses
```
A name indicates what we seek. An address indicates where it is.
```

