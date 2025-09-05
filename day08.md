# Classful Subnetting

* Very specific subnetting architecture that hasn't been used since 1993.

* Class A - Leading Bits (0-127). Network bits: 8
    * Subnet mask `255.0.0.0`
* Class B Leading Bits (128-191) Network bits: 16
    * Subnet mask `255.255.0.0`
* Class C Leading Bits (192-223) Network bits: 24
    * Subnet mask `255.255.255.0`

## The construction of a subnet
* Network address
    * The first IP address of a subnet.
    * Set all host bits to 0.
* First usable host address
    * One number higher than the network address.
* Network broadcast address 
    * The last IP address of a subnet (255 decimal)
* Last usable host address
    * One number lower than the broadcast address.

****************

Completed video #22 lecture of Professor Messer's course. Day nine will continue with the [IPv4 Subnet Masks](https://www.youtube.com/watch?v=p5NJ5Jt6oJo&list=PLG49S3nxzAnl_tQe3kvnmeMid0mjF8Le8&index=23) lecture.

