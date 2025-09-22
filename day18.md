# IPv6 Addressing continued

## IPv6 address compression
* Groups of zeros can be abbreviated witha double colon. Only one of these abbreviations allowed per address.
* Leading zeroes are optional.

## Communicating between IPv4 and IPv6
* Not all devices can talk IPv6
  * Legacy devices embedded systems.

* Alternate forms of communication
  * Tunnel - Encapsulate on protocol within another.
  * Dual-stack - have the option to use both IPv4 and IPv6
  * Translate - Convert between IPv4 and IPv6.
* These are short-term strategies
  * Long term goal should be to migrate to IPv6.

## Tunneling IPv6
* A migration option for temporary use.
* 6 to 4 addressing.
  * Send IPv6 over an existing IPv4 address.
  * NO support for NAT
  * Requires relay routers

## Dual-stack routing
* Use both protocols at the same time.

## Translate between IPv4 and IPv6
* NAT64 - translate between the two protocols
* Requires something in the middle to translate.
  * IPv6 is not backwards compatible with IPv4
* Works with a DNS64 server.

****************
Completed video #32 lecture of Professor Messer's course. Day 19 will continue with the [Static Routing](https://www.youtube.com/watch?v=23a6_qexTvs&list=PLG49S3nxzAnl_tQe3kvnmeMid0mjF8Le8&index=32) lecture.






