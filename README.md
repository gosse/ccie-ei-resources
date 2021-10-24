# CCIE EI Resources 

This is a list of resources for CCIE Enterprise Infrastructure candidates. It is not meant to be exhaustive, please add to it! Pull requests welcome. 

* [0.0 General](#00-general)
* [1.0 Network Infrastructure](#10-network-infrastructure)
* [2.0 Software Defined Infrastructure](#20-software-defined-infrastructure)
* [3.0 Transport Technologies and Solutions](#30-transport-technologies-and-solutions)
* [4.0 Infrastructure Security and Services](#40-infrastructure-security-and-services)
* [5.0 Infrastructure Automation and Programmability](#50-infrastructure-automation-and-programmability)

Legend: 
* 📺 Video
* 🗒️ Cisco Docs 
* 📚 Book
* 📝 RFC/Standard 

--------------------
 
## 0.0 General 

### 0.1 Cisco Resources

* [Official Exam Topics](https://learningcontent.cisco.com/documents/exam-topics/CCIE+Enterprise+Infrastructure+(v1.0+RevA)+Exam+Topics.pdf)
* [CCIE Enterprise Infrastructure Equipment and Software List](https://learningnetwork.cisco.com/s/article/ccie-enterprise-infrastructure-equipment-and-software-list)
* [Cisco CCIE EI Training Tracking Log/Matrix (XLSX)]( https://www.cisco.com/c/dam/en_us/training-events/le31/le46/cln/marketing/learning-matrix/CCIE-Enterprise-Infrastructure-v1-Learning-Matrix.xlsx)
* [CCIE Practical Exam / LAB overview](https://learningnetwork.cisco.com/s/article/ccie-practical-exam-format)
* 📺 [Cisco Live On-Demand Library](https://www.ciscolive.com/global/on-demand-library.html?#/)
* [Cisco DevNet](https://developer.cisco.com/site/networking/)
* [Cisco Design Zone (CVD)](https://www.cisco.com/c/en/us/solutions/design-zone.html)
* [Cisco Communities](https://community.cisco.com/t5/other-network-architecture/bd-p/5981-discussions-other-network-infra)

### 0.2 Paid Training Resources and Bootcamps

* [kbits.live](https://kbits.live/)
* [Micronics CCIE EI v1.0](https://micronicstraining.com/events/ccie-enterprise-infrastructure-v1-o/)
* [Orhan Ergun CCIE EI v1.0](https://orhanergun.net/ccie-enterprise-infrastructure-training/)
* [Network Lessons](https://networklessons.com/cisco/ccie-enterprise-infrastructure)
* [INE CCIE EI v1.0](https://my.ine.com/path/61f74429-8e0c-41b1-ba84-dd542c555df7)
* [Boson NetSim](https://www.boson.com/certification/ccie-enterprise-infrastructure)
* [Lab Minutes](http://www.labminutes.com/)
* [Pluralsight](https://www.pluralsight.com)

### 0.3 Labbing Software/Systems 

* [Cisco dCloud](https://dcloud.cisco.com/)
* [Cisco Modeling Labs - Personal Edition (formally VIRL)](https://learningnetworkstore.cisco.com/cisco-modeling-labs-personal/cisco-cml-personal)
* [Eve-NG](https://www.eve-ng.net/) 
* [GNS3](https://www.gns3.com/)
* [Rack Rental - Cloud My Lab](https://cloudmylab.com/ccieenterpriseinfrastucture/)

### 0.4 Blogroll 

* Coming soon - add your own blog via a pull request! 

## 1.0 Network Infrastructure 

* 🗒️ [Cisco Docs - Cisco IOS XE Gibraltar 16.12.1](https://www.cisco.com/c/en/us/support/ios-nx-os-software/ios-xe-gibraltar-16-12-1/model.html)
* 🗒️ [Cisco Docs - Software Configuration Guide, Cisco IOS Release 15.2(4)E](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst3750x_3560x/software/release/15-2_4_e/configurationguide/b_1524e_consolidated_3750x_3560x_cg.html)

### 1.1 Switched Campus 
  * 🗒️ [Cisco IOS-XE Docs - LAN Switching Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/lanswitch/configuration/xe-16-12/lanswitch-xe-16-12-book.html)
* 1.1.a Switch administration
  * 1.1.a i Managing MAC address table
  * 1.1.a ii Errdisable recovery
  * 1.1.a iii L2 MTU
* 1.1.b Layer 2 protocols
  * 1.1.b i CDP, LLDP
  * 1.1.b ii UDLD
* 1.1.c VLAN technologies
  * 1.1.c i Access ports
  * 1.1.c ii Trunk ports (802.1Q)
  * 1.1.c iii Native VLAN
  * 1.1.c iv Manual VLAN pruning
  * 1.1.c v VLAN database
  * 1.1.c vi Normal range and extended range VLANs
  * 1.1.c vii Voice VLAN
  * 1.1.c viii VTP
* 1.1.d EtherChannel
  * 1.1.d i LACP, static
  * 1.1.d ii Layer 2, Layer 3
  * 1.1.d iii Load balancing
  * 1.1.d iv EtherChannel Misconfiguration Guard
* 1.1.e Spanning- Tree Protocol
  * 🗒️ [Cisco Docs - Understanding Rapid Spanning Tree Protocol (802.1w)](https://www.cisco.com/c/en/us/support/docs/lan-switching/spanning-tree-protocol/24062-146.html)
  * 1.1.e i PVST+, Rapid PVST+, MST
  * 1.1.e ii Switch priority, port priority, path cost, STP timers
  * 1.1.e iii PortFast, BPDU Guard, BPDU Filter
  * 1.1.e iv Loop Guard, Root Guard

### 1.2 Routing Concepts
  * 🗒️ [Cisco Docs - IP Routing](https://www.cisco.com/c/en/us/tech/ip/ip-routing/index.html)
  * 🗒️ [Cisco Docs - IP Routing: Protocol-Independent Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_pi/configuration/xe-16-12/iri-xe-16-12-book.html)
* 1.2.a Administrative distance
* 1.2.b VRF-lite
* 1.2.c Static routing
* 1.2.d Policy Based Routing
* 1.2.e VRF aware routing with any routing protocol
* 1.2.f Route filtering with any routing protocol
* 1.2.g Manual summarization with any routing protocol
  * 🗒️ [IP Routing: EIGRP Configuration Guide, Cisco IOS XE Gibraltar 16.12.x - Route Summarization](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_eigrp/configuration/xe-16-12/ire-xe-16-12-book/ire-enhanced-igrp.html#GUID-5EC23579-53DC-4AC4-AED4-9C4748965BD8)
  * 🗒️ [IP Routing: EIGRP Configuration Guide, Cisco IOS XE Gibraltar 16.12.x - Configuring Summary Addresses](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_eigrp/configuration/xe-16-12/ire-xe-16-12-book/ip6-route-eigrp-xe.html#GUID-84817AC5-D58C-4C83-9FC4-0434A46CA5FA)
  * 🗒️ [IP Routing: OSPF Configuration Guide, Cisco IOS XE Gibraltar 16.12.x- Configuring Route Summarization Between OSPF Areas](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_ospf/configuration/xe-16-12/iro-xe-16-12-book/iro-cfg.html#GUID-3507B8ED-037F-465D-AFEE-F3543EE65692)
  * 🗒️ [IP Routing: BGP Configuration Guide, Cisco IOS XE Gibraltar 16.12.x  - BGP Route Aggregation](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_bgp/configuration/xe-16-12/irg-xe-16-12-book/configuring-a-basic-bgp-network.html#GUID-6DDE6391-682B-4A6F-8659-149272213871)
  * 🗒️ [Understanding Route Aggregation in BGP](https://www.cisco.com/c/en/us/support/docs/ip/border-gateway-protocol-bgp/5441-aggregation.html#aggregatingwithouttheassetargument)
* 1.2.h Redistribution between any pair of routing protocols
  * 🗒️ [Cisco Troubleshooting TechNote - Redistributing Routing Protocols](https://www.cisco.com/c/en/us/support/docs/ip/enhanced-interior-gateway-routing-protocol-eigrp/8606-redist.html)
  * 🗒️ [Cisco Troubleshooting TechNote - Understanding Redistribution of OSPF Routes into BGP](https://www.cisco.com/c/en/us/support/docs/ip/border-gateway-protocol-bgp/5242-bgp-ospf-redis.html)
* 1.2.i Routing protocol authentication
  * [Managing Authentication Keys](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_pi/configuration/xe-16-12/iri-xe-16-12-book/iri-iprouting.html#GUID-121832C5-C558-4B9D-AEDB-4DA6AAE1B5FA)
  * [IP EIGRP Route Authentication](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_eigrp/configuration/xe-16-12/ire-xe-16-12-book/ire-rte-auth.html)
  * [IPv6 EIGRP - Configuring EIGRP Route Authentication](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_eigrp/configuration/xe-16-12/ire-xe-16-12-book/ip6-route-eigrp-xe.html#GUID-2ED9BBAC-0271-4361-B486-F060BB1D4096)
  * [EIGRP/SAF HMAC-SHA-256 Authentication](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_eigrp/configuration/xe-16-12/ire-xe-16-12-book/ire-sha-256.html)
  * [IP Routing: OSPF Configuration Guide, Cisco IOS XE Gibraltar 16.12.x - Configuring Interface Parameters](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_ospf/configuration/xe-16-12/iro-xe-16-12-book/iro-cfg.html#GUID-4AABEB56-2125-488B-B5A4-A5650F3159BB)
  * [OSPFv2 Cryptographic Authentication](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_ospf/configuration/xe-16-12/iro-xe-16-12-book/iro-ospfv2-crypto-authen-xe.html)
  * [IPv6 Routing: OSPFv3 Authentication Support with IPsec](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_ospf/configuration/xe-16-12/iro-xe-16-12-book/ip6-route-ospfv3-auth-ipsec.html#GUID-BCDA2C85-53CA-4400-B6D9-C2A908AD87B8)
  * [OSPFv3 Authentication Trailer](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_ospf/configuration/xe-16-12/iro-xe-16-12-book/iro-ospfv3-authtrailer.html)
  * [TCP Authentication Option](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_pi/configuration/xe-16-12/iri-xe-16-12-book/tcp-ao.html)
  * [BGP Support for TCP Authentication Option](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_bgp/configuration/xe-16-12/irg-xe-16-12-book/bgp-support-for-TCP-AO.html)
* 1.2.j Bidirectional Forwarding Detection
  * 🗒️ [Cisco Docs - IP Routing: BFD Configuration Guide, Cisco IOS XE Gibraltar 16.12.x](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_bfd/configuration/xe-16-12/irb-xe-16-12-book.html)

### 1.3 EIGRP

* 🗒️ [Cisco Docs - IP Routing: EIGRP Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_eigrp/configuration/xe-16-12/ire-xe-16-12-book.html)
* 📺 [Cisco Live - EIGRP](https://www.ciscolive.com/global/on-demand-library.html?search=EIGRP#/)
* 📺 [Cisco Live - EIGRP Deployment in Modern Networks](https://www.ciscolive.com/global/on-demand-library.html?search=BRKRST-2336#/)
* 📺 [Cisco Live - Intro to EIGRP](https://www.ciscolive.com/global/on-demand-library.html#/session/1576111569617001f7vL)
* 📺 [Cisco Live - Troubleshooting EIGRP Networks](https://www.ciscolive.com/global/on-demand-library.html#/session/1542224322901001ryRy)
* 1.3.a Adjacencies
* 1.3.b Best path selection
  * 1.3.b i RD, FD, FC, successor, feasible successor
  * 1.3.b ii Classic Metrics and Wide Metrics
* 1.3.c Operations
  * 1.3.c i General operations
  * 1.3.c ii Topology table
  * 1.3.c iii Packet types
  * 1.3.c iv Stuck In Active
  * 1.3.c v Graceful shutdown
* 1.3.d EIGRP load-balancing
  * 1.3.d i Equal-cost
  * 1.3.d ii Unequal-cost
  * 1.3.d iii Add-path
* 1.3.e EIGRP Named Mode
* 1.3.f Optimization, convergence and scalability
  * 1.3.f i Fast convergence requirements
  * 1.3.f ii Query propagation boundaries
  * 1.3.f iii IP FRR (single hop)
  * 1.3.f iv Leak-map with summary routes
  * 1.3.f v EIGRP stub with leak map

### 1.4 OSPF (v2 and v3)

* 📝 [RFC 2328 OSPF Version 2](https://tools.ietf.org/html/rfc2328)
* 📝 [RFC 5340 OSPF for IPv6](https://tools.ietf.org/html/rfc5340)
* 📚 [OSPF - anatomy of an Internet Routing Protocol]()
* 📚 [Cisco IP Routing - Packet Forwarding and Intra-domain Routing Protocols]()
* 📚 [Routing TCP/IP Vol. 1]()
* 🗒️ [Cisco IOS-XE Docs - OSPF Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_ospf/configuration/xe-16-10/iro-xe-16-10-book.html)
* 1.4.a Adjacencies
* 1.4.b Network types, area types
* 1.4.c Path preference
* 1.4.d Operations
  * 1.4.d i General operations
  * 1.4.d ii Graceful shutdown
  * 1.4.d iii GTSM (Generic TTL Security Mechanism)
* 1.4.e Optimization, convergence and scalability
  * 1.4.e i Metrics
  * 1.4.e ii LSA throttling, SPF tuning, fast hello
  * 1.4.e iii LSA propagation control (area types)
  * 1.4.e iv Stub router
  * 1.4.e v Loop-free alternate
  * 1.4.e vi Prefix suppression

### 1.5 BGP

* 📺 [Google Talks - BGP at 18](https://www.youtube.com/watch?v=_Mn4kKVBdaM)
* 📺 [Cisco Live BRKRST-3321 Scaling BGP](https://www.ciscolive.com/c/global/on-demand-library.html?search=BRKRST-3321#/)
* 📚 [Internet Routing Architectures](https://learning.oreilly.com/library/view/internet-routing-architectures/157870233X/)
* 📚 [Routing TCP/IP, Vol II](https://learning.oreilly.com/library/view/routing-tcpip-volume/9780134192772/)
* 📚 [Practical BGP](https://learning.oreilly.com/library/view/practical-bgp/0321127005/)
* 📚 [Optimal Routing Design](https://learning.oreilly.com/library/view/optimal-routing-design/1587051877/)
* 🗒️ [Cisco IOS-XE Docs - IP Routing: BGP Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/iproute_bgp/configuration/xe-16-10/irg-xe-16-10-book.html)
* 1.5.a IBGP and EBGP peer relationships
  * 1.5.a i Peer-group/update-group, template
  * 1.5.a ii Active, passive
  * 1.5.a iii Timers
  * 1.5.a iv Dynamic neighbors
  * 1.5.a v 4-bytes AS numbers
  * 1.5.a vi Private AS
* 1.5.b Path selection
  * 1.5.b i Attributes
  * 1.5.b ii Best path selection algorithm
  * 1.5.b iii Load-balancing
* 1.5.c Routing policies
  * 1.5.c i Attribute manipulation
  * 1.5.c ii Conditional advertisement
  * 1.5.c iii Outbound Route Filtering
  * 1.5.c iv Standard and extended communities
  * 1.5.c v Multi-homing
* 1.5.d AS path manipulations
  * 1.5.d i local-AS, allowas-in, remove-private-as
  * 1.5.d ii Prepend
  * 1.5.d iii Regexp
* 1.5.e Convergence and scalability
  * 1.5.e i Route reflector
  * 1.5.e ii Aggregation, as-set
* 1.5.f Other BGP features
  * 1.5.f i Multipath, add-path
  * 1.5.f ii Soft reconfiguration, Route Refresh

### 1.6 Multicast

* 🗒️ [Cisco IOS-XE Docs - PIM Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/ipmulti_pim/configuration/xe-16-10/imc-pim-xe-16-10-book.html)
* 🗒️ [Cisco IOS-XE Docs - IGMP configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/ipmulti_igmp/configuration/xe-16-10/imc-igmp-xe-16-10-book.html)
* 📚 [Routing TCP/IP, Vol II](https://learning.oreilly.com/library/view/routing-tcpip-volume/9780134192772/)
* 📚 [Developing IP Multicast Networks](https://www.ciscopress.com/store/developing-ip-multicast-networks-volume-i-paperback-9781587142895)
* 📚 [Interdomain Multicast Routing: Practical Juniper Networks and Cisco Systems Solutions](https://learning.oreilly.com/library/view/interdomain-multicast-routing/0201746123/)
* 📺 [Introduction to IP Multicast - DGTL-BRKIPM-1261](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/1573153548896001JvK2)
* 📺 [Multicast Troubleshooting - BRKIPM-2264](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/1573153548978001J6Mh)
* 1.6.a Layer 2 multicast
  * 1.6.a i IGMPv2, IGMPv3
  * 1.6.a ii IGMP Snooping, PIM Snooping
    * 📝 [RFC 4541](https://datatracker.ietf.org/doc/html/rfc4541)
  * 1.6.a iii IGMP Querier
  * 1.6.a iv IGMP Filter
  * 1.6.a v MLD 
* 1.6.b Reverse path forwarding check
* 1.6.c PIM
  * 1.6.c i Sparse Mode
  * 1.6.c ii Static RP, BSR, AutoRP
  * 1.6.c iii Group to RP Mapping
  * 1.6.c iv Bidirectional PIM
  * 1.6.c v Source-Specific Multicast
  * 1.6.c vi Multicast boundary, RP announcement filter
  * 1.6.c vii PIMv6 Anycast RP
    * [IP Multicast: PIM Configuration Guide, Cisco IOS XE Gibraltar 16.12.x | Chapter: Configuring Basic IP Multicast in IPv6 Networks](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/ipmulti_pim/configuration/xe-16-12/imc-pim-xe-16-12-book/imc-basic-ipv6.html)
  * 1.6.c viii IPv4 Anycast RP using MSDP
  * 1.6.c ix Multicast multipath
    * [Load Splitting IP Multicast Traffic over ECMP](https://www.cisco.com/c/en/us/td/docs/ios/12_4t/ip_mcast/configuration/guide/mctlsplt.html)

## 2.0 Software Defined Infrastructure 

### 2.1 Cisco SD Access

* 🗒️ [Cisco Docs - DNA Assurance User Guide 1.3.1](https://www.cisco.com/c/en/us/td/docs/cloud-systems-management/network-automation-and-management/dna-center-assurance/1-3-1-0/b_cisco_dna_assurance_1_3_1_0_ug.html)
* 📺 [Cisco Live - Cisco DNA Center - Network operation and cross architecture integration with IT Service Management - DGTL-BRKNMS-2458](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/1573153550070001JR6j)
* 📺 [Cisco Live - Cisco DNA Center: The evolution from traditional Management to Intent-Based Automation and Assurance - DGTL-BRKNMS-2031](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/1573153549708001JKkm)
* 📺 [Cisco Live - DNA-C Design and Policy - DEMCOC-602](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/1590057454471001bDUv)
* 📺 [Cisco Live - Policy and Segmentation with Cisco DNA Center - DEMCRS-601](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/1590057460045001bOTB)
* 📺 [Cisco Live - SD-Access Fabric, Why is My Salsa So Tasty? How SD-Access Solves Enterprise Challenges - DLBTEC-51](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/15892240689180019WZ6)
* 📺 [Cisco Live - SD Access : Troubleshooting the fabric - DGTL-BRKARC-2020](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/1573153537677001Jo5z)
* 🗒️ [Cisco CVD - Software Defined Access Design Guide](https://www.cisco.com/c/dam/en/us/td/docs/solutions/CVD/Campus/CVD-Software-Defined-Access-Design-Sol1dot2-2018DEC.pdf)
* 🗒️ [Cisco CVD - SD Access Deployment Guide](https://www.cisco.com/c/dam/en/us/td/docs/solutions/CVD/Campus/CVD-Software-Defined-Access-Segmentation-Design-Guide-2018MAY.pdf)
* 📚 [Cisco Software-Defined Access (August 2020)](https://learning.oreilly.com/library/view/cisco-software-defined-access/9780136448341/)
* 📚 [Cisco Digital Network Architecture: Intent-based Networking for the Enterprise](https://learning.oreilly.com/library/view/cisco-digital-network/9780134723952/)
* 2.1.a Design a Cisco SD Access solution
  * 2.1.a i Underlay network (IS-IS, manual/PnP)
  * 2.1.a ii Overlay fabric design (LISP, VXLAN, Cisco TrustSec)
  * 2.1.a iii Fabric domains (single-site and multi-site using SD-WAN transit)
* 2.1.b Cisco SD Access deployment
  * 2.1.b i Cisco DNA Center device discovery and device management
  * 2.1.b ii Add fabric node devices to an existing fabric
  * 2.1.b iii Host onboarding (wired endpoints only)
  * 2.1.b iv Fabric border handoff
* 2.1.c Segmentation
  * 2.1.c i Macro-level segmentation using VNs
  * 2.1.c ii Micro-level segmentation using SGTs (using Cisco ISE)
* 2.1.d Assurance
  * 2.1.d i Network and client health (360)
  * 2.1.d ii Monitoring and troubleshooting

### 2.2 Cisco SD-WAN

* 🗒️ [Cisco Docs - vManage How Tos](https://sdwan-docs.cisco.com/Product_Documentation/vManage_How-Tos/Configuration)
* 🗒️ [Cisco Docs - Device Configuration Template](https://sdwan-docs.cisco.com/Product_Documentation/vManage_How-Tos/Configuration/Create_a_Device_Configuration_Template)
* 🗒️ [Cisco Design Zone for Branch, WAN, and Internet Edge](https://www.cisco.com/c/en/us/solutions/design-zone/networking-design-guides/branch-wan-edge.html)
* 🗒️ [Cisco SD-WAN Design Guide](https://www.cisco.com/c/en/us/td/docs/solutions/CVD/SDWAN/cisco-sdwan-design-guide.html)
* 📺 [Cisco Live - SD-WAN](https://www.ciscolive.com/global/on-demand-library.html?search=SD-WAN)
* 📺 [Cisco Live - Building and Using Policies with Cisco SD-WAN](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/1573153553280001Jhr9)
* 📺 [Cisco Live - Delivering Cisco Next Generation SD-WAN with Viptela - BRKCRS-2110](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/1573153542774001Jftj)
* 📺 [Cisco Live - Designing for a Cloud-Ready Secure WAN Architecture - DLBTEC-50](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/1588378944558001YIgm)
* 📺 [Cisco Live - SD-WAN and Network Functions Service Chaining - DGTL-BRKENS-1100](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/1572617849119001peXV)
* 📺 [Cisco Live - SD-WAN, deployment strategies, managing and monitoring - BRKRST-2519](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/1573153553037001JE2U)
* 📺 [Cisco Live - SD-WAN Enterprise Routing Platform Overview - DGTL-BRKARC-2102](https://www.ciscolive.com/global/on-demand-library.html?search=DGTL-BRKARC-2102#/session/1571753540403001fdv8)
* 📚 [CCNP Enterprise Design ENSLD 300-420 Official Cert Guide Chapter 11](https://learning.oreilly.com/library/view/ccnp-enterprise-design/9780136575160/)
* 📚 [Software Defined Wide Area Networks (Aug 2020)](https://www.ciscopress.com/store/cisco-software-defined-wide-area-networks-designing-9780136533177)
* 2.2.a Design a Cisco SD-WAN solution
  * 2.2.a i Orchestration plane (vBond, NAT)
  * 2.2.a ii Management plane (vManage)
  * 2.2.a iii Control plane (vSmart, OMP)
  * 2.2.a iv Data plane (vEdge/cEdge)
* 2.2.b WAN edge deployment
  * 2.2.b i Onboarding new edge routers
  * 2.2.b ii Orchestration with zero-touch provisioning/Plug-And-Play
  * 2.2.b iii OMP
  * 2.2.b iv TLOC
* 2.2.c Configuration templates
* 2.2.d Localized policies
* 2.2.e Centralized policies


## 3.0 Transport Technologies and Solutions 

### 3.1 MPLS

* 🗒️ [Cisco Docs - MPLS Label Distribution Protocol Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/mp_ldp/configuration/xe-16/mp-ldp-xe-16-book.html)
* 🗒️ [Cisco Docs - MPLS: Layer 3 VPNs Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/mp_l3_vpns/configuration/xe-16-12/mp-l3-vpns-xe-16-12-book.html)
* 📺 [Cisco Live - MPLS](https://www.ciscolive.com/global/on-demand-library.html?search=MPLS#/)
* 📺 [Cisco Live - Introduction to MPLS - DGTL-BRKMPL-1100](https://www.ciscolive.com/global/on-demand-library.html?search.event=ciscoliveus2020&cid=20200618atttu&ccid=cc001205&dtid=oemrft001460&fix=0#/session/1573153549100001JJkV)
* 3.1.a Operations
  * 3.1.a i Label stack, LSR, LSP
  * 3.1.a ii LDP
  * 3.1.a iii MPLS ping, MPLS traceroute
* 3.1.b L3VPN
  * 3.1.b i PE-CE routing
  * 3.1.b ii MP-BGP VPNv4/VPNv6
  * 3.1.b iii Extranet (route leaking)

### 3.2 DMVPN
* 🗒️ [Cisco Docs - Dynamic Multipoint VPN Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/sec_conn_dmvpn/configuration/xe-16-12/sec-conn-dmvpn-xe-16-12-book.html)
* 📺 [Cisco Live - Demystifying DMVPN BRKSEC-3052](https://www.ciscolive.com/global/on-demand-library.html?search=dmvpn#/session/1484773617788001WfsN)
* 📺 [Cisco Live - DMVPN](https://www.ciscolive.com/global/on-demand-library.html?search=DMVPN#/)
* 📺 [Cisco Live -  Advanced Concepts of DMVPN BRKSEC-4054](https://www.ciscolive.com/c/global/on-demand-library.html?search=dmvpn#/session/1484773617075001W8sx)
* 3.2.a Troubleshoot DMVPN Phase 3 with dual-hub
  * 📺 [Cisco Live -  Troubleshooting Dynamic Multipoint VPN (DMVPN) BRKSEC-3052](https://www.ciscolive.com/global/on-demand-library.html?search=dmvpn#/session/1454486436572001QYT4)
  * [Cisco Docs - Most Common DMVPN Troubleshooting Solutions](https://www.cisco.com/c/en/us/support/docs/security/dynamic-multipoint-vpn-dmvpn/111976-dmvpn-troubleshoot-00.html)
  * 3.2.a i NHRP
  * 3.2.a ii IPsec/IKEv2 using pre-shared key
  * 3.2.a iii Per-Tunnel QoS
    * 🗒️ [Cisco Docs - DMVPN - Per-Tunnel QoS](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/sec_conn_dmvpn/configuration/15-mt/sec-conn-dmvpn-15-mt-book/sec-conn-dmvpn-per-tunnel-qos.html)
    * 🗒️ [Networking with Fish:  Playing in the Lab: DMVPN and Per-Tunnel QoS](https://www.networkingwithfish.com/playing-in-the-lab-dmvpn-and-per-tunnel-qos/)
* 3.2.b Identify use-cases for FlexVPN
  * 🗒️ [Cisco Docs - FlexVPN and Internet Key Exchange Version 2 Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/sec_conn_ike2vpn/configuration/xe-16-12/sec-flex-vpn-xe-16-12-book.html)
  * 📺 [Cisco Live - FlexVPN](https://www.ciscolive.com/global/on-demand-library.html?search=Flexvpn#/)
  * 📺 [Cisco Live - Advanced IPSec designs with FlexVPN BRKSEC-3036](https://www.ciscolive.com/global/on-demand-library.html?search=flexvpn#/session/14479207933930017VDW)
  * 📺 [Cisco Live - Advanced IOS FlexVPN Lab LTRSEC-3004](https://www.ciscolive.com/global/on-demand-library.html?search=flexvpn#/session/LTRSEC-3004)
  * 📺 [Cisco Live - FlexVPN Remote-Access, IoT & Site- to-Site Advanced Crypto Design BRKSEC-3054](https://www.ciscolive.com/global/on-demand-library.html?search=flexvpn#/session/1564677379756001J63z)
  * 3.2.b i Site-to-site, Server, Client, Spoke-to-Spoke
  * 3.2.b ii IPsec/IKEv2 using pre-shared key
  * 3.2.b iii MPLS over FlexVPN
    * [FlexVPN and Internet Key Exchange Version 2 Configuration Guide, Cisco IOS Release 15M&T - Configuring MPLS over FlexVPN](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/sec_conn_ike2vpn/configuration/15-mt/sec-flex-vpn-15-mt-book/sec-cfg-mpls-flex.html)
    * [Dynamic Multipoint VPN Configuration Guide, Cisco IOS XE Gibraltar 16.12.x - Configuring MPLS over DMVPN](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/sec_conn_dmvpn/configuration/xe-16-12/sec-conn-dmvpn-xe-16-12-book/sec-conn-dmvpn-xe-configure.html)


## 4.0 Infrastructure Security and Services 

### 4.1 Device Security on Cisco IOS XE

* 4.1.a Control plane policing and protection
  * 🗒️ [Cisco Docs - QoS: Policing and Shaping Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/qos_plcshp/configuration/xe-16-12/qos-plcshp-xe-16-12-book/qos-plcshp-ctrl-pln-plc.html)
* 4.1.b AAA
  * 🗒️ [Cisco Docs - Authentication Authorization and Accounting Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/sec_usr_aaa/configuration/xe-16-12/sec-usr-aaa-xe-16-12-book.html)
  * [Cisco Docs - Security Configuration Guide, Cisco IOS XE Gibraltar 16.12.x - Configuring Control Plane Policing](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sec/b_1612_sec_9300_cg/configuring_control_plane_policing.html)

### 4.2 Network Security

* 4.2.a Switch security features
  * [Cisco Live - Attacks on Network Infrastructure](https://www.ciscolive.com/c/dam/r/ciscolive/us/docs/2019/pdf/BRKSEC-1032.pdf)
  * 4.2.a i VACL, PACL
    * 🗒️ [Cisco Docs - C3750X - Chapter: Configuring Network Security with ACLs](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst3750x_3560x/software/release/15-0_1_se/configuration/guide/3750xcg/swacl.html)
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: IPv4 ACLs](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sec/b_1612_sec_9300_cg/configuring_ipv4_acls.html)
  * 4.2.a ii Storm control
    * 🗒️ [Cisco Docs - C3750X - Chapter: Configuring Port-Based Traffic Control](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst3750x_3560x/software/release/15-0_1_se/configuration/guide/3750xcg/swtrafc.html)
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring Port-Based Traffic Control](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sec/b_1612_sec_9300_cg/configuring_port_based_traffic_control.html)
  * 4.2.a iii DHCP Snooping, DHCP option 82
    * 🗒️ [Cisco Docs - C3750X - Chapter: Configuring DHCP Features and IP Source Guard](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst3750x_3560x/software/release/15-0_1_se/configuration/guide/3750xcg/swdhcp82.html)
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring DHCP](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/ip/b_1612_ip_9300_cg/configuring_dhcp.html)
    * [INE - Understanding DHCP Option 82](https://blog.ine.com/2009/07/22/understanding-dhcp-option-82)
  * 4.2.a iv IP Source 
    * 🗒️ [Cisco Docs - C3750X - Chapter: Configuring DHCP Features and IP Source Guard](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst3750x_3560x/software/release/15-0_1_se/configuration/guide/3750xcg/swdhcp82.html)
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring IP Source Guard](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sec/b_1612_sec_9300_cg/configuring_ip_source_guard.html)
  * 4.2.a v Dynamic ARP Inspection
    * 🗒️ [Cisco Docs - C3750X - Chapter: Configuring Dynamic ARP Inspection](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst3750x_3560x/software/release/15-0_1_se/configuration/guide/3750xcg/swdynarp.html)
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring Dynamic ARP Inspection](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sec/b_1612_sec_9300_cg/configuring_dynamic_arp_inspection.html)
  * 4.2.a vi Port Security
    * 🗒️ [Cisco Docs - C3750X - Chapter: Configuring Port-Based Traffic Control](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst3750x_3560x/software/release/15-0_1_se/configuration/guide/3750xcg/swtrafc.html)
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Port Security](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sec/b_1612_sec_9300_cg/port_security.html) 
  * 4.2.a vii Private VLAN
    * 🗒️ [Cisco Docs - C3750X - Chapter: Configuring Private VLANs](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst3750x_3560x/software/release/15-0_1_se/configuration/guide/3750xcg/swpvlan.html)
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring Private VLANs](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/vlan/b_1612_vlan_9300_cg/configuring_private_vlans.html)
* 4.2.b Router security features
  * 4.2.b i IPv6 Traffic Filters
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: IPv6 ACLs](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sec/b_1612_sec_9300_cg/configuring_ipv6_acls.html)
  * 4.2.b ii IPv4 Access Control Lists
    * 🗒️ [Cisco Docs - Security Configuration Guide: Access Control Lists](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/sec_data_acl/configuration/xe-16-10/sec-data-acl-xe-16-10-book.html)
    * 🗒️ [Cisco Docs - Chapter: Information about Network Security with ACLs](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst3750x_3560x/software/release/15-2_4_e/configurationguide/b_1524e_consolidated_3750x_3560x_cg/b_1524e_consolidated_3750x_3560x_cg_chapter_0101101.html)
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: IPv4 ACLs](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sec/b_1612_sec_9300_cg/configuring_ipv4_acls.html)
  * 4.2.b iii Unicast Reverse Path Forwarding
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring Unicast Reverse Path Forwarding](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/rtng/b_1612_rtng_9300_cg/configuring_unicast_reverse_path_forwarding.html)
    * 🗒️ [Cisco Docs - Security Configuration Guide: Unicast Reverse Path Forwarding, Cisco IOS XE Gibraltor 16.12.x](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/sec_data_urpf/configuration/xe-16-12/sec-data-urpf-xe-16-12-book/cfg-unicast-rpf.html)
* 4.2.c IPv6 infrastructure security features
  * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring IPv6 First Hop Security](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sec/b_1612_sec_9300_cg/configuring_ipv6_first_hop_security.html)
  * 🗒️ [Cisco Docs - C3750X - Configuring First Hop Security in IPv6](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst3750x_3560x/software/release/15-2_4_e/configurationguide/b_1524e_consolidated_3750x_3560x_cg/b_1524e_consolidated_3750x_3560x_cg_chapter_0110011.html?bookSearch=true#d307081e4854a1635)
  * 4.2.c i RA Guard
  * 4.2.c ii DHCP Guard
  * 4.2.c iii Binding table
  * 4.2.c iv Device tracking
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring SISF-Based Device Tracking](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sec/b_1612_sec_9300_cg/configuring_sisf_based_device_tracking.html)
  * 4.2.c v ND Inspection/Snooping
  * 4.2.c vi Source Guard
* 4.2.d IEEE 802.1X Port-Based Authentication
  * 🗒️ [Cisco Docs - 15M&T - Chapter: Configuring IEEE 802.1X Port-Based Authentication](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/sec_usr_8021x/configuration/15-mt/sec-user-8021x-15-mt-book/config-ieee-802x-pba.html)
  * 🗒️ [Cisco Docs - 3750X - Chapter: Configuring IEEE 802.1x Port-Based Authentication](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst3750x_3560x/software/release/15-2_4_e/configurationguide/b_1524e_consolidated_3750x_3560x_cg/b_1524e_consolidated_3750x_3560x_cg_chapter_01010.html)
  * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring IEEE 802.1x Port-Based Authentication](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sec/b_1612_sec_9300_cg/configuring_ieee_802_1x_port_based_authentication.html)
  * 4.2.d i Device roles, port states
  * 4.2.d ii Authentication process
  * 4.2.d iii Host modes


### 4.3 System Management
  * 🗒️ [Cisco Docs - System Management Configuration Guide, Cisco IOS XE Gibraltar 16.12.x (Catalyst 9300 Switches)](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sys_mgmt/b_1612_sys_mgmt_9300_cg.html)
* 4.3.a Device management
  * 4.3.a i Console and VTY
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Controlling Switch Access with Passwords and Privilege Levels](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sec/b_1612_sec_9300_cg/controlling_switch_access_with_passwords_and_privilege_levels.html)
  * 4.3.a ii SSH, SCP
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Secure Copy](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sys_mgmt/b_1612_sys_mgmt_9300_cg/secure_copy.html)
  * 4.3.a iii RESTCONF, NETCONF
* 4.3.b SNMP
  * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring Simple Network Management Protocol](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/nmgmt/b_1612_nmgmt_9300_cg/configuring_simple_network_management_protocol.html)
  * 4.3.b i v2c
  * 4.3.b ii v3
* 4.3.c Logging
  * 4.3.c i Local logging, syslog, debugs, conditional debugs
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring System Message Logs](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sys_mgmt/b_1612_sys_mgmt_9300_cg/configuring_system_message_logs.html)]
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Conditional Debug and Radioactive Tracing](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sys_mgmt/b_1612_sys_mgmt_9300_cg/conditional_debug_and_radioactive_tracing.html)
  * 4.3.c ii Timestamps

### 4.4 Quality of Service
  * 🗒️ [Cisco Docs - QoS Modular QoS Command-Line Interface Configuration Guide, Cisco IOS XE Gibraltar 16.12.x](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/qos_mqc/configuration/xe-16-12/qos-mqc-xe-16-12-book.html)
  * 📺 [Cisco Live - QoS](https://www.ciscolive.com/global/on-demand-library.html?search=qos#/)
* 4.4.a End to end L3 QoS using MQC
  * 4.4.a i DiffServ
  * 4.4.a ii CoS and DSCP Mapping
  * 4.4.a iii Classification
  * 4.4.a iv Network Based Application Recognition (NBAR)
  * 4.4.a v Marking using IP Precedence, DSCP, CoS
  * 4.4.a vi Policing, shaping
  * 4.4.a vii Congestion management and avoidance
  * 4.4.a viii HQoS, Sub-rate Ethernet Link

### 4.5 Network Services

* 4.5.a First-Hop Redundancy Protocols
  * 🗒️ [Cisco Docs - First Hop Redundancy Protocols Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/ipapp_fhrp/configuration/xe-16/fhp-xe-16-book.html)
  * 4.5.a i HSRP, GLBP, VRRP
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring HSRP](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/ip/b_1612_ip_9300_cg/configuring___hsrp.html)
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring GLBP](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/ip/b_1612_ip_9300_cg/configuring_glbp.html)
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: VRRPv3 Protocol Support](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/ip/b_1612_ip_9300_cg/vrrpv3_protocol___support.html)
  * 4.5.a ii Redundancy using IPv6 RS/RA
* 4.5.b Network Time Protocol
  * 🗒️ [Cisco Docs - Chapter: Network Time Protocol](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/bsm/configuration/xe-16/bsm-xe-16-book/bsm-time-calendar-set.html)
  * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Administering the Device](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sys_mgmt/b_1612_sys_mgmt_9300_cg/administering_the_device.html)
  * [Ivan Pepelnjak - Secure Time Management (PDF)](https://learning.nil.com/assets/Tips-/Secure-Time-Management.pdf)
  * [Cisco Troubleshooting TechNotes - Troubleshoot Network Time Protocol (NTP)](https://www.cisco.com/c/en/us/support/docs/ip/network-time-protocol-ntp/108076-ntp-troubleshoot.html)
  * [Cisco Technology White Paper - Network Time Protocol: Best Practices White Paper](https://www.cisco.com/c/en/us/support/docs/availability/high-availability/19643-ntpm.html)
  * 4.5.b i Master, client
  * 4.5.b ii Authentication
* 4.5.c DHCP on Cisco IOS
  * 🗒️ [Cisco Docs - IP Addressing: DHCP Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/ipaddr_dhcp/configuration/xe-16-10/dhcp-xe-16-10-book.html)
  * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring DHCP](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/ip/b_1612_ip_9300_cg/configuring_dhcp.html)
  * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: DHCP Gleaning](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/ip/b_1612_ip_9300_cg/dhcp_gleaning.html)
  * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: DHCP Options Support](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/ip/b_1612_ip_9300_cg/dhcp_options_support.html)
  * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: DHCPv6 Options Support](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/ip/b_1612_ip_9300_cg/dhcpv6_options_support.html)
  * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: DHCPv6 Relay Source Configuration](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/ip/b_1612_ip_9300_cg/dhcpv6_relay_source_configuration.html)
  * 4.5.c i Client, server, relay
  * 4.5.c ii Options
  * 4.5.c iii SLAAC/DHCPv6 interaction
  * 4.5.c iv Stateful, stateless DHCPv6
  * 4.5.c v DHCPv6 Prefix Delegation
* 4.5.d IPv4 Network Address Translation
  * 🗒️ [Cisco Docs - IP Addressing: NAT Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/ipaddr_nat/configuration/xe-16-10/nat-xe-16-10-book.html)
  * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring Network Address Translation](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/ip/b_1612_ip_9300_cg/configuring_network_address_translation.html) 
  * 4.5.d i Static NAT, PAT
  * 4.5.d ii Dynamic NAT, PAT
  * 4.5.d iii Policy-based NAT, PAT
  * 4.5.d iv VRF aware NAT, PAT
  * 4.5.d v IOS-XE VRF-Aware Software Infrastructure (VASI) NAT
    * 🗒️ [Cisco Docs - Configure VRF-Aware Software Infrastructure (VASI) NAT on IOS-XE](https://www.cisco.com/c/en/us/support/docs/ip/network-address-translation-nat/200255-Configure-VRF-Aware-Software-Infrastruct.html)
  
### 4.6 Network optimization

* 4.6.a IP SLA
  * 🗒️ [Cisco IOS-XE Docs - IP SLA](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/ipsla/configuration/xe-16-10/sla-xe-16-10-book.html)
  * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring Service Level Agreements](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/nmgmt/b_1612_nmgmt_9300_cg/configuring_service_level_agreements.html)
  * 4.6.a i ICMP probes
  * 4.6.a ii UDP probes
  * 4.6.a iii TCP probes
* 4.6.b Tracking object
  * 🗒️ [Cisco IOS-XE Docs - IP Application Services Configuration Guide Chapter: Configuring Enhanced Object Tracking](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/ipapp/configuration/xe-16-10/iap-xe-16-10-book/iap-eot.html)
  * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring Enhanced Object Tracking](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/ip/b_1612_ip_9300_cg/configuring_enhanced___object_tracking.html)
* 4.6.c Flexible Netflow
  * 🗒️ [Cisco IOS-XE Docs Flexible NetFlow Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/fnetflow/configuration/xe-16-10/fnf-xe-16-10-book.html)
  * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring Flexible NetFlow](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/nmgmt/b_1612_nmgmt_9300_cg/configuring_flexible_netflow.html)

### 4.7 Network operations

* 4.7.a Traffic capture
  * 4.7.a i SPAN
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring SPAN and RSPAN](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/nmgmt/b_1612_nmgmt_9300_cg/configuring_span_and_rspan.html)
  * 4.7.a ii RSPAN
    * 🗒️ [Cisco IOS 15.2 Docs - Chapter: Configuring SPAN and RSPAN](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst3750x_3560x/software/release/15-2_4_e/configurationguide/b_1524e_consolidated_3750x_3560x_cg/b_1524e_consolidated_3750x_3560x_cg_chapter_0101000.html?bookSearch=true)
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring SPAN and RSPAN](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/nmgmt/b_1612_nmgmt_9300_cg/configuring_span_and_rspan.html)
  * 4.7.a iii ERSPAN
    * 🗒️ [Cisco IOS-XE Docs - Chapter: Configuring ERSPAN](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/lanswitch/configuration/xe-16-10/lanswitch-xe-16-10-book/lnsw-conf-erspan.html?bookSearch=true) 
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring ERSPAN](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/nmgmt/b_1612_nmgmt_9300_cg/configuring_erspan.html)
  * 4.7.a iv Embedded Packet Capture
    * 🗒️ [Cisco IOS-XE Docs -  Chapter: Embedded Packet Capture Overview](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/epc/configuration/xe-16-10/epc-xe-16-10-book/nm-packet-capture-xe.html)
    * 🗒️ [Cisco Docs - Embedded Packet Capture for Cisco IOS and IOS-XE Configuration Example](https://www.cisco.com/c/en/us/support/docs/ios-nx-os-software/ios-embedded-packet-capture/116045-productconfig-epc-00.html)
    * 🗒️ [Cisco Docs - C9300 16.12 - Chapter: Configuring Packet Capture](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/nmgmt/b_1612_nmgmt_9300_cg/configuring_packet_capture.html)
* 4.7.b Cisco IOS-XE troubleshooting tools
  * 4.7.b i Packet Trace
    * 🗒️ [Cisco Docs - Troubleshooting Guide, Cisco IOS XE Release 3S (Cisco ASR 1000)](https://www.cisco.com/c/en/us/td/docs/routers/asr1000/troubleshooting/guide/Tblshooting-xe-3s-asr-1000-book.html)
    * 🗒️ [Cisco Docs - IOS-XE Datapath Packet Trace Feature](https://www.cisco.com/c/en/us/support/docs/content-networking/adaptive-session-redundancy-asr/117858-technote-asr-00.html)
  * 4.7.b ii Conditional debugger (debug platform condition)

## 5.0 Infrastructure Automation and Programmability 

* 📚 [Network Programmability and Automation](https://learning.oreilly.com/library/view/network-programmability-and/9781491931240/)
* 📺 [Cisco DevNet - Learn network programmability basics](https://developer.cisco.com/video/net-prog-basics/)

### 5.1 Data encoding formats

* 5.1.a JSON
  * 📝 [RFC 8259](https://tools.ietf.org/html/rfc8259)
  * 📝 [ISO/IEC 21778:2017 Information technology — The JSON data interchange syntax](https://www.iso.org/standard/71616.html)
  * 📝 [ECMA-404 The JSON Data Interchange Format (PDF)](https://www.ecma-international.org/publications/files/ECMA-ST-ARCH/ECMA-404%201st%20edition%20October%202013.pdf)
* 5.1.b XML
  * 📝 [RFC 3470 / BCP 70 Guidelines for the Use of Extensible Markup Language (XML) within IETF Protocols](https://tools.ietf.org/html/rfc3470)
  * 📝 [W3C Extensible Markup Language (XML) 1.0 (Fifth Edition)](https://www.w3.org/TR/REC-xml/)


### 5.2 Automation and scripting

* 5.2.a EEM applets
  * 🗒️ [Cisco IOS-XE Docs - Embedded Event Manager Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/eem/configuration/xe-16-10/eem-xe-16-10-book.html)
* 5.2.b Guest shell
  * 🗒️ [Cisco IOS-XE Docs - Programmability Configuration Guide, Cisco IOS XE Gibraltar 16.12.x Chapter: Guest Shell](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/prog/configuration/1612/b_1612_programmability_cg/guest_shell.html)
  * 5.2.b i Linux environment
  * 5.2.b ii CLI Python module
    * 🗒️ [Cisco IOS-XE Docs - Programmability Configuration Guide, Cisco IOS XE Gibraltar 16.12.x Chatper: CLI Python Module](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/prog/configuration/1612/b_1612_programmability_cg/cli_python_module.html)
  * 5.2.b iii EEM Python module
    * 🗒️ [Cisco IOS-XE Docs - Programmability Configuration Guide, Cisco IOS XE Gibraltar 16.12.x Chapter: EEM Python Module](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/prog/configuration/1612/b_1612_programmability_cg/eem_python_module.html)

### 5.3 Programmability

* [Python requests library](https://requests.readthedocs.io/en/master/)
* [Postman](https://www.postman.com/)
* 5.3.a Interaction with vManage API
  * 🗒️ [DevNet Learning Track - Cisco SD-WAN Programmability](https://developer.cisco.com/learning/tracks/sd-wan_programmability)
  * 📺 [Pluralsight - Automating Cisco SD-WAN Operations Using APIs](https://app.pluralsight.com/library/courses/automating-cisco-sd-wan-operations-using-apis/table-of-contents)
  * [vManage API Docs](https://developer.cisco.com/docs/sdwan/#!introduction)
  * 5.3.a i Python requests library and Postman
  * 5.3.a ii Monitoring endpoints
  * 5.3.a iii Configuration endpoints
* 5.3.b Interaction with Cisco DNA Center API
  * 📺 [Pluralsight - Automating Cisco DNA Center Operations Using APIs](https://app.pluralsight.com/library/courses/automating-cisco-dna-center-operations-using-apis/)
  * 📺 [Pluralsight - Managing Cisco Products Using Advanced API-based Methods (Module 2)](https://app.pluralsight.com/library/courses/managing-cisco-products-advanced-api-methods/table-of-contents)
  * 🗒️ [DevNet Learning Track - Programming the Digital Network Architecture (Cisco DNA)](https://developer.cisco.com/learning/tracks/programming-dna)
  * 🗒️ [DevNet Learning Track - Cisco DNA Center Programmability](https://developer.cisco.com/learning/tracks/dnacenter-programmability)
  * 5.3.b i HTTP request (GET, PUT, POST) via Python requests library and Postman
* 5.3.c Interaction with Cisco IOS XE API
  * 🗒️ [Cisco IOS XE REST API Management Reference Guide](https://www.cisco.com/c/en/us/td/docs/routers/csr1000/software/restapi/restapi/RESTAPIintro.html)
  * 📺 [Pluralsight - Provisioning and Managing Networks Using Common Automation Tools](https://app.pluralsight.com/library/courses/provisioning-managing-networks-common-automation-tools/table-of-contents)
  * 🗒️ [DevNet Learning Track - IOS XE Programmability](https://developer.cisco.com/learning/tracks/iosxe-programmability)
  * 🗒️ [DevNet Learning Track - Network Programmability for Network Engineers](https://developer.cisco.com/learning/tracks/netprog-eng)
  * 5.3.c i Via NETCONF/YANG using Python ncclient library
  * 5.3.c ii Via RESTCONF/YANG using Python requests library and Postman
* 5.3.d Deploy and verify model-driven telemetry
  * 🗒️ [Cisco Docs - Programmability Configuration Guide](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/prog/configuration/1610/b_1610_programmability_cg/model_driven_telemetry.html)
  * 🗒️ [DevNet Docs - Streaming Telemetry](https://developer.cisco.com/docs/ios-xe/#!streaming-telemetry-quick-start-guide)
  * 🗒️ [DevNet Learning Labs - Introduction to Telemetry on IOS XE](https://developer.cisco.com/learning/modules/iosxe_telemetry/intro_telemetry_on_xe/step/1)
  * 🗒️ [DevNet Learning Labs - Enabling Telemetry On IOS XE](https://developer.cisco.com/learning/modules/iosxe_telemetry/enabling_telemetry_on_iosxe/step/1)
  * [PluralSight - Deploying Network Configuration Management and Telemetry Solutions](https://app.pluralsight.com/library/courses/deploying-network-configuration-management-telemetry-solutions/table-of-contents)
  * 5.3.d i Configure on-change subscription using gRPC


