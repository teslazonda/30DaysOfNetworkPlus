# Zero trust

## Zero trust
* Many networks are relatively open on the inside.
  * Once you're through the firewall, there are few security controls.
* Zero trust is a holistic approach to network security.
  * Covers every device, every process, every person.
* Everything must be verified
  * Nothing is inherently trusted
  * Multi-factor authentication, encryption, system permissions, additional firewalls, monitoring and analytics, etc.

## Policy-based authentication
* Adaptive identity
  * Consider the source and the requested resources
  * Multiple risk indicators - relationship to the organization, physical location, type of connection, IP address, etc.
  * Make the authentication stronger, if needed.

* Policy-driven access control
  * Combine the adaptive identity with a predefined set of rules.
  * Evaluates each access decision based on policy and other information.
  * Grant, deny, or revoke.

## Authorization
* Authentication is complete
  * We can trust your identity.
* Authorization process is also required
  * Determine which applications and data are accessible.
* Different rights depending on the user
  * Help desk technicians can view the hardware database.
  * Help desk managers can modify the database.
  * Other users have no access.
* Can include other criteria
  * Location, device certificate validation, time of day, etc.

## Least privilege access
* Rights and permissions should be set to the bare minimum.
  * You only get exactly what's needed to complete your objective.
* All user accounts must be limited
  * Applications should run with minimal privileges
* Don't allow users to run with administrative privileges.
  * Limits the scope of malicious behavior.

## Secure Access Service Edge (SASE)
* Update secure access for cloud services.
  * Securely connect from different locations.
* Secure Access Service Edge (SASE)
  * A "next generation" VPN.
* Security technologies are in the cloud.
  * Located close to existing cloud services.
* SASE clients on all devices.
  * Streamlined and automatic.

****************

Completed video #29 lecture of Professor Messer's course. Day 15 will continue with the [Infrastructure as Code](https://www.youtube.com/watch?v=n6jIaKWixF4&list=PLG49S3nxzAnl_tQe3kvnmeMid0mjF8Le8&index=30) lecture.


