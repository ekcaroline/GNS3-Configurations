# GNS3-Configurations
A collection of configurations crafted within GNS3, each tailored to meet specific requirements.

## OSPF_HW
I've configured the routing to facilitate communication between any subnet and any other subnet:
- All networks have been configured as point-to-point connections.
- Interfaces facing LANs are set to passive mode to avoid flooding the LANs with HELLO messages.
- OSPF messages are authenticated as per the configuration.
- Passwords are encrypted for security.
- IP addresses on all LANs are dynamically assigned through DHCP.
- Privileged modes on all Cisco routers are password protected.
