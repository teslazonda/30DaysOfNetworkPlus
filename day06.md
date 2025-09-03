# Copper Connectors, Network Topologies, Network Architectures

## Copper Connectors

### RJ11 connector
* Registered Jack type11
* Telephone and DSL connections.

### RJ45 connector
* Registered Jack type 45
* 8 position, 8 conductor
    * Ethernet

### F-connector
* Coaxial able
* Cable television infrastructure. (DOCSIS).

### BNC connector
* Bayonet Neill-Concelman
* Another common coaxial cable connector.
    * Common with twinax and DS3 WAN links.
    * Video connections
* Secure connections by twisting and locking the cable in place.


## Network Topologies

### Star / Hub and Spoke.
* Used in most large networks.
* All devices are connected to a central device.
* Switched Ethernet networks.

### Mesh
* Multiple links to the same place.
* Redundancy, fault-tolerance, load balancing.
* Used in wide area networks (WANSs).

### Hybrid
* A combination of one or more physical topologies.

### Spine and leaf 
* Each leaf switch connects to each leaf switch.
* Leaf switches do not connect to each other, same for spine switches.
* Top-of-rack switching. Makes cabling easy, it's redundant and fast.

### Point-to-point
* One-to-one-connection
* Older WAN connections.
* Connections between buildings.

## Network Architectures

### Three-tier architecture
* Core
    * Center of the network.
    * Web servers, databases, applications.
    * Many people need access.
* Distribution
    * Midpoint between the core and the users.
    * Communication between access switches.
* Access
    * Where the users connect.
    * End stations, printers.

### Collapsed core
* Two-tier model
* For smaller organizations

### Traffic flows
* Traffic flows within a data center
    * East-west traffic
        * Traffic between devices in the same data center.
        * Fast response times.
    * North-South traffic
        * Ingress/egress to an outside device.
        * Different security posture than east-west.