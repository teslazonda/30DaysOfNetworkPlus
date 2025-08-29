# The OSI model and IP

## OSI model

### Layer 1 - Physical Layer

Troubleshooting problems in cables, physical connections.

### Layer 2 - Data Link Layer
Called the "switching layer"
Includes:
* MAC Adress on Ethernet.

### Layer 3 - Network Layer
The "routing" layer
* Internet Protocol (IP)
* Fragments frams to traverse networks.

### Layer 4 - Transport Layer
The "post office" layer
* TCP or UDP act at this layer

### Layer 5 - Session Layer
* Communication management between devices
    * start, stop, restart
* Control protocols, tunneling protocols

### Layer 6 - Presentation Layer
* Character encoding
* Application encryption

### Layer 7 - Application Layer
* The layer we see as a user
* HTTP, FTP, DNS

## Internet Protocol (IP)

### TCP vs UDP
Both operate at Layer 4, transport layer

TCP:
* "Reliable" delivery through ACK, acknowledment of data received.

UPD:
* "Unreliable" no formal open or close to the connection, or error recovery.

Non-ephemeral ports are ports 0 through 1,023

Ephemeral ports are ports 1024 through 65,535

TCP port numbers are not the same as UDP port numbers. Two applications can each use the same port number for each protocol without issue.

****************

Completed first 7 video lectures of Professor Messer's course. Day two will continue with the [Common Ports](https://www.youtube.com/watch?v=jX1pobYmZdE&list=PLG49S3nxzAnl_tQe3kvnmeMid0mjF8Le8&index=9) lecture.