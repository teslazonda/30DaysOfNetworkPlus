# Binary Math and IPv4 Addressing

## Binary Math
* A byte is 8 bits, or 8 1s and 0s in binary.
* The binary `00000010`is `2` in decimal.

## IPv4 Addressing
* IP Address `192.168.1.165`
    * Every device needs a unique IP address
* Subnet mask `255.255.255.0`
    * Used by the local device to determine what subnet it's on
        * The subnet mask isn't usually transmitted over the network.
        * You'll ask for the subnet mask all the time.
* Default Gateway, `192.168.1.1`
    * The router that allows you to communicate outside of your local subnet.
    * The default gateway must be an IP address on the local subnet.

### Special IPv4 Addresses
* Loopback address
    * An address to yourself.
    * Ranges from `127.0.0.1` through `127.255.255.254`.
    * An easy way to self-reference.
* Reserved Addresses
    * Set aside for future use or testing
    * `240.0.0.1` through `254.255.255.254`
    * All 'Class E' addresses.
* Virtual IP address
    * Not associated with a physical network adapter.
    * Virtual machine, internal router address.

### DHCP
* Dynamic Host Configuration Protocol
    * Provides automatic addresses and IP configuration for almost all devices.

### Automatic Private IP addressing (APIPA)
* A link-local address.
* Can only communicate to other local devices.
* No forwarding by routers.
* Reserved `169.254.0.1` through `169.254.255.254`.

### Private IP address ranges
* We use Private IPv4 addresses, which are not accessible over the internet, because there are far more devices in the world than the number of available IP addresses.
* RFC 1918 defines the ranges of private IP addresses.
    * `10.0.0.0 - 10.255.255.255.255` single class A. `255.0.0.0` subnet mask. (24 bit Host Id size)
    * `172.16.0.0 - 172.31.255.255` 16 contiguous class Bs. `255.240.0.0` subnet mask. (20 bit Host Id size)
    * `192.168.0.0 - 192.168.255.255` 256 contiguous class Cs. `255.255.0.0` subnet mask. (16 bit Host Id size)

****************

Completed video #21 lecture of Professor Messer's course. Day eight will continue with the [Classful Subnetting](https://www.youtube.com/watch?v=XVIOtj-Z9m0&list=PLG49S3nxzAnl_tQe3kvnmeMid0mjF8Le8&index=22) lecture.

