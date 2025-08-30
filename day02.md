# Common Ports

## tcp/20 tcp/21
### FTP - File Transfer Protocol
* 20 (active mode data)
* 21 (control) - authenticate with a username and password.

## tcp/22
### SSH - Secure Shell
* Text-based console communication.
* Encrypted communication link.

### SFTP - Secure File Transfer Protocol
* Generic file transfer with security (an encrypted connection).
* Uses SSH and port 22.

## tcp/23
### Telnet - Telecommunication Network
* Console access (similar to SSH).
* In the clear communication (not encrypted).

## tcp/25 tcp/587
### SMTP - Simple Mail Transfer Protocol
* Server to server email transfer.
* Port 25 - plaintext.
* Port 587 - uses TLS encryption.
* Used to send mail from a device to a mail server. Often configured on mobile devices and email clients.
* Other mail protocols are IMAP, POP3

## udp/53, tcp/53
### DNS - Domain Name System
* Converts names to IP addresses.
* Large transfers may use `tcp/53`

## udp/67, udp/68
### DHCP - Dynamic Host Configuration Protocol
* Automated configuration of IP address, subnet mask and other options.
    * Requires a DHCP server
    * Server, appliance, integrated into a SOHO router.
* Dynamic/pooled
    * IP addresses are assigned in real-time from a pool.
    * Each system is given a lease, must renew at set intervals.
* DHCP reservation
    * Addresses are assigned by MAC address in the DHCP server.
    * Quickly manage addresses from one location.

## udp/69
### TFTP - Trivial File Transfer Protocol
* Read and write files.
* No authentication.
* Useful when starting a system.
    * Transfer configuration files.

## tcp/80, tcp/443
### HTTP and HTTPS - Hypertext Transfer Protocol
* Communication in the browser and other applications
* In the clear or encrypted
    * SSL or TLS

## udp/123
### NTP - Network Time Protocol
* Switches, routers, firewalls, servers, workstations
    * Every device has its own clock.

## udp/161
### SNMP - Simple Network Management Protocol
* Gather statistics from network devices.
* v1 - original
    * In the clear, structured tables
* v2 - next version
    * Data types
    * Bulk transfers
    * Not encrypted
* v3 - Secure standard
    * Message integrity
    * Authentication
    * Encryption
* SNMP traps `udp/162`
    * Alerts and notifications from network devices

## tcp/389, tcp/636
### LDAP/LDAPS - Lightweight Directory Access Protocol
* Store and retrieve information in a network directory.
* LDAPS (LDAP Secure)
    * Non-standard implementation of LDAP over SSL on `tcp/636`.

## tcp/445
### SMB - Server Message Block
* Protocol used by Windows for File sharing, printer sharing.
    * Also called CIFS
* Integrated into Windows Operating system.

## udp/514
### Syslog
* Standard for message logging.
* Usually a central log collector.
* Uses a lot of disk space.

## tcp/1433
### Microsoft SQL Server
* MS-SQL

## tcp/3389
### RDP - Remote Desktop Protocol
* Share a desktop form a remote location over `tcp/3389`.
    * Connection to an entire desktop or just an application.

## tcp/5060, tcp/5061
### SIP - Session Initiation Protocol
* Voice over IP (VoIP) signaling.
* Setup and manage VoIP session.
* Extend voice communication.

****************

Completed first video #8 lecture of Professor Messer's course. Day three will continue with the [Other Useful Protocols](https://www.youtube.com/watch?v=5BahWbszVAY&list=PLG49S3nxzAnl_tQe3kvnmeMid0mjF8Le8&index=9) lecture.