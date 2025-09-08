# Calculating IPv4 Subnets and Hosts

Why subnet the network?
* We use routers to serve as an endpoint for an IP address, so many different devices can talk to each other.

## VLSM (Variable Length Subnet Masks)
* Class-based networks are inefficient
  * The subnet mask is based on the network class
* Allow network administrators to define their own masks.
  * Customize the subnet mask to specific network requirements.
* use different subnet masks in the same classful network.
  * 10.0.0.0/8 is the class A network.
  * 10.0.1.0/24 is would be VLSM.

## Defining subnets
* IP address: `10.0.0.0`
  * Class A, subnet mask: `255.0.0.0`
  * Class A, subnet mask: `255.0.0.0`
Number of subnets = 2 ** (subnet bits)
Hosts per subnet = 2 ** (host bits) - 2

IP address: `192.168.11.0/26`
* Class C address
* 11111111.11111111.11111111.11000000
* Network = 24 bits, Subnet bits = 2, Host bits = 6.
  * Total subnets = 2**2 = 4
  * Hosts per subnet = 2**6 -2 = 62
