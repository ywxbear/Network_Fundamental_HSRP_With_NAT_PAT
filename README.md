# Network Fundamental Hot Standby Router Protocol (HSRP) Set Up (Cisco Packet Tracer - For study purpose only)
Here in this project i will configure a Hot Standby Router Protocol (HSRP) architecture. These designs can be expanded to create very complex architectures depending on the network requirements.

Hot Standby Router Protocol (HSRP) is a CISCO proprietary protocol, which provides redundancy for a local subnet. In HSRP, two or more routers gives an illusion of a virtual router. HSRP allows you to configure two or more routers as standby routers and only a single router as active router at a time. All the routers in a single HSRP group shares a single MAC address and IP address, which acts a default gateway to the local network. The Active router is responsible for forwarding the traffic. If it fails, the Standby router takes up all the responsibilities of the active router and forwards the traffic.

![network design](/hsrp.PNG)

## How to Run
Install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) and then simply open the [HSRP.pkt](https://github.com/weixiong15/Network_Fundamental_HSRP/blob/master/HSRP.pkt). The whole network is in working condition. You can check it by sending a packet from one system to another or through using the PING command in the Cisco Packet Tracer.

**All Router and Switch passwords: cisco**

This solution works for version 6.2 or above of Cisco Packet Tracer.
