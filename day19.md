# Static Routing

## Routing tables
* The router has a simple job
  * The underlying technology is relatively complex.
* Identify the destination IP address
  * It's in the packet.
* If the destination IP address is on a locally connected subnet
  * Forward the packet to the local device.
* if the destination IP address is on a remote subnet
  * Forward to the next-hop router/gatway
  * This "map" of forwarding locations is the routing table.

## Static routing
* Administratively define the routes
  * You're in control
* Advantages
  * Easy to configure on small networks
  * No overhead from routing protocols
  * Easy to configure on stub networks (only one way out)
  * More secure - no routing protocols to analyze
* Disadvantages
  * Difficult to administer on larger networks
  * NO automatic method to prevent routing loops
  * If there's a network change, you have to manually update the routes.
  * No automatic rerouting if an outage occurs.

****************
Completed video #33 lecture of Professor Messer's course. Day 20 will continue with the [Dynamic Routing](https://www.youtube.com/watch?v=YRZxshxI1xs&list=PLG49S3nxzAnl_tQe3kvnmeMid0mjF8Le8&index=33) lecture.






