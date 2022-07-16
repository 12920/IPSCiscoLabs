# IPSCiscoLabs
Lab Configuration Files of Cisco Certified Courses
Steps to Deploy Topologies in EVE-NG

Pre-requisites
1. WinSCP or FileZilla
2. Enable either one of the following:
•	Telnet
•	Putty
•	Rlogin Client
3. Added required images in EVE-ng
4. Windows Client Side  https://www.eve-ng.net/index.php/download/
Steps:
1. Enter the provided credentials and sign in. 
 
2. After login, you will be required to first create a folder for your lab. 
 
Note: Make one case study for one chapter. Labs can be more than one in each lab however the basics of case study should be same. 
3. To create a folder, write your lab name in the space given by Add Folder. 
 
4. After making folder, open that particular folder. 
 
5. From the top given menu, click on Add new lab.
 
6. Enter the following details for your lab and click on Save.
•	Name of Lab
•	Author
Note: Leave the remaining options as default. 
 
7. Click on the lab to open. 
 

 
8. Use the left side given menu to start configure the topology. 
 
9. Add an object option allow you to create Nodes, Network, Pictures, Shapes, and Text. Click on Node to add switch, router, server, PC, etc. 
 
10. Select your required image from the list. 
 
11. Enter the required details. Then, click on Save.  
 
12. You will see the node in the Lab screen. 
 
13. Similarly, you can add a switch. 
 
14. You will see the following nodes. 
15. Also, you can change the configuration of nodes by using right click on that node and edit it. 
 
16. To connect router with switch, take a cursor to router and drag the connection to switch.
 
17. Enter the connection name and click on Save. 

 
18. You will see the blue connection between the nodes. 
 
Note: Similarly, you can connect and configure multiple nodes that are required for your topology. 
19. Now, click on More actions from left side given menu. 
20. Click on Start all nodes.
 
21. You will see the nodes in blue after they will become active. 
 
22. To start configuration on each node, go to the node and click on it. 
23. Click on Open SSH, Telnet, or Rlogin client.
 
Note: You should enable Telnet or Rlogin client settings on your laptop. Otherwise, CLI will not appear. Should go to control panel to enable the settings. 
24. After that, you will see the CLI for that particular node. 
 

Steps to deploy more attractive topology. 
25. Use the following options to add text, box, back ground colors, borders as well. 
 
 
26. Similarly, you can add shape using the Custom shapes.
 
 
 
Similarly, you can find multiple topologies to develop the visualization according to your case study. 
 
Note: After doing all the configurations, export all the configuration by clicking export all CFGs from the left-hand menu in more actions option. 

Troubleshooting Labs
If we faced any issue while doing labs on eve-ng, following are the tips should be followed.
1.	Strong internet connection will be required, if your internet is dropped somewhere, your configuration will be lost.
2.	Save the lab frequently after done one configuration step like assign IP address save it immediately with write command.
3.	If your topology is stuck, click on Refresh topology from the left-hand pane.
4.	If you are not verifying your lab after doing all correct configurations, use the following commands to know the issue.
a.	show ip interface brief
b.	show ip route
c.	traceroute <ip>
d.	show interface status   
5. Router issue –VRouter. (Copy paste the same router again).

