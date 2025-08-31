# Other Useful Protocols

## ICMP - Internet Control Message Protocol
* Carried by IP, not used for data transfer.
* Devices can request and reply to administrative requests.

## GRE - Generic Routing Encapsulation
* Two endpoints appear to be directly connected to each other.
* No built-in encryption.

## VPN - Virtual Private Networks
* Encrypted data traversing a public network.
* Concentrator - encryption or decryption device.
    * Firewalls often act as VPN concentrators in site-to-site VPNs.

## IPSec - Internet Protocol Security
* Security for OSI Layer 3.
    * Authentication and encryption for every packet.
* Confidentiality and integrity/anti replay.
    * Encryption and packet signing.
* Very standardized
    * Common to use with multi-vendor implementations.
* Two core IPSec protocols
    * Authentication Header (AH)
    * Encapsulation Security Payload (ESP)
* Tunnel mode is more secure than Transport mode because the IP header is masked with IPSEc headers.

## IKE - Internet Key Exchange
* Agree on encryption/decryption keys
    * Without sending key across the network
    * Builds s security association (SA)
* Phase I
    * Use Diffie-Hellman to create a shared key on `udp/500`.
    * ISAKMP (Internet Security Association and Key Management Protocol).
* Phase II
    * Coordinate ciphers and key sizes.
    * Negotiate an inbound and outbound SA for IPSec.

****************

Completed video #9 lecture of Professor Messer's course. Day three will continue with the [Network Communication](https://www.youtube.com/watch?v=9Vx-awO6qfc&list=PLG49S3nxzAnl_tQe3kvnmeMid0mjF8Le8&index=10) lecture.
