IP Address Configuration and RIP Version 2 Setup

1. Work Completed This Period:
   
Figure 1: Cisco Packet Tracer
<img width="1440" height="900" alt="Screenshot 2026-07-27 at 4 32 05 PM" src="https://github.com/user-attachments/assets/06bb39c4-7854-4739-a24d-04cfb9e3da67" />

Cisco Packet Tracer was used to design configure and test the network before implementation.  
The objective of using Packet Tracer in this project was to simulate the network environment, configure IP addressing and RIP Version 2, verify connectivity and identify configuration errors in a safe virtual environment Its advantages include easy network simulation, troubleshooting and testing without requiring physical networking devices.

During this period, I configured the IP addresses for the router interfaces in Cisco Packet Tracer and verified that all interfaces were operating correctly.

<img width="562" height="253" alt="Screenshot 2026-07-27 at 8 55 41 PM" src="https://github.com/user-attachments/assets/c5b85c22-5e98-4096-b0cd-5b5860401523" />


After configuring the IP addresses, I configured RIP Version 2 by enabling RIP on both routers, adding the required networks, and disabling auto-summary, the routing configuration was verified using the show ip route command, and connectivity was tested using the ping command.

Figure 2: Router1 (show ip route)

<img width="1440" height="900" alt="Screenshot 2026-07-27 at 7 12 19 PM" src="https://github.com/user-attachments/assets/490a0de3-174b-4cb6-9dd3-dbaf168f2991" />


Figure 3: Router0 (show ip route and ping)

<img width="1440" height="900" alt="Screenshot 2026-07-27 at 7 10 05 PM" src="https://github.com/user-attachments/assets/330f5056-e854-4a5e-8318-17ce19137288" />

The routing table displayed the learned routes correctly, and all ping tests were completed successfully.  

2. One Key Decision Made During This Period: 
One important decision during this period was to use RIP Version 2 as the routing protocol. 

It was selected because it is easy to configure, supports dynamic routing, and is suitable for connecting the two WAN networks in this project.

3. One Problem Encountered:
   
Figure 4: Initial Network Topology
￼￼<img width="1440" height="900" alt="Screenshot 2026-07-27 at 7 06 06 PM" src="https://github.com/user-attachments/assets/2bfe864a-9eeb-4827-ac56-d295991cb1c3" />

During the configuration process, the connection between Router0 and Switch0 was inactive because the cable was connected to the wrong router interface.
The issue was identified during testing after reconnecting the cable to the correct interface, the link became active successfully, and the routing and connectivity tests were completed without any further problems, final network topology after completing the configuration.

Figure 5: Final Network Topology
<img width="1440" height="900" alt="Screenshot 2026-07-27 at 7 37 27 PM" src="https://github.com/user-attachments/assets/22429529-9eaf-4bc4-88fe-3a78deda7d81" />

4. Plan for the Next Period:
The next step is to review the network configuration, verify routing and connectivity between all devices, and prepare the project for final submission.
