# Magic Number Subnetting

## Four important addresses
* Network address / subnet ID
  * The first address in the subnet.
* Broadcast address
  * The last address in the subnet.
* First available host address
  * One less than the broadcast address.

## CIDR to decimal
CIDR | Decimal

`/9` | `255.128.0.0`
`/10` | `255.192.0.0`
`/11` | `255.224.0.0`
`/12` | `255.240.0.0`
`/13` | `255.248.0.0`
`/14` | `255.252.0.0`
`/15` | `255.254.0.0`
`/16` | `255.255.0.0`
`/17` | `255.255.128.0`

CIDR          |   Decimal
`/9 /17 /25`  | `128`
`/10 /18 /26` | `192`
`/11 /19 /27` | `224`
`/12 /20 /28` | `240`
`/13 /21 /29` | `248`
`/14 /22 /30` | `252`
`/15 /23 /31` | `254`
`/16 /24 /32` | `255`


****************

Completed video #25 lecture of Professor Messer's course.


