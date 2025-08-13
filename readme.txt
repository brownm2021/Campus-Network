 Cisco Packet Tracer Lab – Network Infrastructure Design

Hello and welcome! 👋

This repository contains a Cisco Packet Tracer lab focused on multi-VLAN routing, HSRP redundancy and port security. 

Lab Overview
• 	Refer to topology.png for a visual overview of the network layout.
• 	The lab simulates a scalable enterprise network with:
• 	Multiple VLANs (PCs, Phones, Wi-Fi, Management)
• 	HSRP configuration for gateway redundancy
• 	Rapid PVST+ with root bridge alignment to HSRP roles
• 	Trunked port channels between distribution switches
• 	DHCP, DNS, and file services simulated via server nodes

Purpose: 
This lab was completed to demonstrate:
• 	Hands-on proficiency with Cisco IOS
• 	Layer 2 and Layer 3 redundancy techniques
• 	Network troubleshooting and documentation habits
• 	Alignment of STP and HSRP for optimal traffic flow

What I learned:

• HSRP and STP Alignment: I learned how to strategically assign STP root priorities to match HSRP active routers, ensuring optimal traffic paths and failover behavior.

• Layer 2/3 Redundancy: Implementing EtherChannel and HSRP across distribution switches taught me how to build fault-tolerant topologies that maintain high availability.

• Structured IP Planning: Designing scalable IP schemes with loopbacks, routed links, and VLAN interfaces helped me refine my subnetting and documentation practices.

• Troubleshooting Methodology: I practiced isolating issues using comparative analysis between working and broken configurations, reinforcing my stepwise troubleshooting approach.

• Problem-Solving Under Complexity: Throughout the lab, I encountered several configuration errors due to the complexity of the topology. To overcome these, I consulted Cisco forums, reached out to technical experts, and leveraged AI tools to diagnose and remediate issues—strengthening my ability to troubleshoot in real-world environments.