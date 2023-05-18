# Secure-connection-between-two-branch-office-using-cisco-packet-tracer
# Introduction:
The purpose of this project is to design a secure network connection between two branch offices using Cisco Packet Tracer. The two branch offices are located in different cities and need to communicate securely to ensure the confidentiality, integrity, and availability of data transferred between them. And to design and implement a network with inter-VLAN routing and DHCP configuration using Cisco packet tracer. The network consists of differnt  VLANs and a DHCP server to assign IP addresses to devices on the network.The network will allow devices on different VLANs to communicate with each other.And provide an overview of layer 2 security and its importance in network infrastructure.
 # Design:
The network design consists of two branch offices, each with a Cisco router, a Cisco switch, and  computers. The routers are connected to each other via a VPN tunnel and static and default routing protocols, which provides a secure and encrypted communication channel between the two branch offices. Each computer is connected to the switch, and the switch is connected to the router.And to network design consists of different VLANs ,each with cisco switchs. The switches are connected to a router that provides inter-VLAN routing .The DHCP servers are configured in routers to provide IP addresses to devices on each VLAN
The VPN tunnel is created using the IPsec protocol, which provides a secure and encrypted connection between the two routers. The IPsec protocol uses two main components: the Authentication Header (AH) and the Encapsulating Security Payload (ESP). The AH provides authentication and integrity protection for the IP packet, while the ESP provides confidentiality and integrity protection.
# Layer 2 security design and configuration
# 1.BPDU Guard:
 * Implement STP security measures, such as BPDU Guard and root Guard , on Cisco Packet Tracer switches.
 * Configure BPDU Guard and Root Guard settings to protect against rogue switches and unauthorized changes.

# 2.DHCP snooping:
 * Enable DHCP snooping on cisco packet tracer switches.
 * Configure trusted and untrusted ports and verify the correct operation of DHCP snooping.
# 3.Port security:
 * Implement port security measures, such as MAC address filtering and sticky MAC addresses ,on Cisco Packet Tracer switches.
 * configure port security setting , including maximum allowed MAC addresses and violation actions.
 
# To configure the VPN tunnel, the following steps were taken:
 1 Configure the IP addresses of the routers and computers.
 
 2 Configure the VPN parameters on both routers, including the encryption algorithm, pre-shared key, and tunnel mode.
 
 3 Test the VPN connection by pinging the computers from each other.
 
 4.In addition to the VPN tunnel, the network also includes access control lists (ACLs) on the routers to control access to the network resources. The ACLs are configured to allow only authorized traffic and block all other traffic.
 # To configure inter-VLAN routing, the following steps were taken:
 
 1 Configure the IP addresses of the switches and the router.
 
 2 Create differnt  VLANs on each switch and assign ports to each VLAN.
 
 3 Configure trunk and access ports on the switches to allow traffic from all VLANs to pass through.
 
 4 Configure subinterfaces on the router for each VLAN and assign IP addresses to the subinterfaces.
 
 5 Configure the router to enable inter-VLAN routing.
 
 # To configure DHCP, the following steps were taken:
 1.Configure a DHCP pool on each DHCP server in routers for each VLAN.
 
 2.Configure the DHCP server to assign IP addresses, subnet masks, default gateways, and DNS servers to devices on each VLAN.
 
 3.Configure the switches to forward DHCP requests to the DHCP server on the same VLAN.
# Conclusion:
In conclusion, the design of a secure network connection between two branch offices using Cisco Packet Tracer was successful. The network provides a secure and encrypted communication channel between the two branch offices, ensuring the confidentiality, integrity, and availability of data transferred between them. The use of ACLs provides an additional layer of security by controlling access to the network resources.

 

