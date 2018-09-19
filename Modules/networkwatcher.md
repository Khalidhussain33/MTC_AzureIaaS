# Network Watcher

Network watcher is an Azure service that allow you to capture network traffic to an Azure endpoint.  You can trigger this service from an alert and then start to capture network traffic that can then be analyzed by your IT staff.

**Purpose of lab**

In this lab is to capture packets to your virtual machine, use the new traffic analysis tool, and various other features of network watcher.

**Estimated time: 15 minutes**

1. In the Azure Portal select All Services from the menu on the left
2. In the context menu select Network Watcher
3. In the Network Watcher blade from the overview section expands the regions in the middle pane
4. Scroll down to East US 2 and verify is enabled

* Note if it’s not enabled Right click on the region and enable

5. In the Network Watcher blade under Monitoring select Topology
6. In the Topology blade select the drop down menu under subscriptions  MTC Azure Workshop 2 (or your subscription)
7. In the Topology blade select the drop down menu under Resource Group select ResstudentX (where X is your assigned number)
8. In the Topology blade select the drop down menu under Virtual Network and select ResStudentX-Vnet1

* Note from this view we can see each VM, the subnet, network interface, and firewall 

9. In the Network Watcher blade under Network diagnostic tools select IP flow verify
10. In the Ip flow verify blade under Resource Group select ResStudentx (where X is your assigned number)
11. In the Ip flow verify blade under virtual machine select ReswebXA (where X is your assigned number)
12. In the Ip flow verify blade under Packet details select Outbound for the direction
13. In the Ip flow verify blade under Packet details in the local port in 50000
14. In the Ip flow verify blade under Packet details in the Remote IP input 172.x.x.4 (where X is your assigned number)
15. In the Ip flow verify blade under Packet details in the Remote port input 53  Check

* Note this will test if the ports/protocols are allowed between the two end points

16. In the Network Watcher blade Network diagnostic tools select Next Hop
17. In the Next hop blade under Resource Group select ResStudentx (where X is your assigned number)
18. In the Next hop blade under virtual machine select ReswebXA (where X is your assigned number)
19. In the Next hop blade under Destination IP input 172.x.x.4 (where X is your assigned number)  Next hop

* Note you can see the next hop goes through Vnet Peering, you can use this to troubleshoot user defined routes or traffic flow on your virtual networks.

20. In the Network Watcher blade under Network diagnostic tools select Security Group view
21. In the Security Group view blade under Resource Group select ResStudentx (where X is your assigned number)
22. In the Security Group view blade under virtual machine select ReswebXA (where X is your assigned number)

* note here we can see all the firewall policies applied to the VMs network interface, subnet, and combination of the two

23. In the Security Group view blade select subnet, and then network interface
24. In the Network Watcher blade under Network diagnostic tools select Packet capture  Add
25. In the Add packet capture blade under Resource Group select ResStudentx (where X is your assigned number)
26. In the Add packet capture blade under virtual machine select ReswebXA (where X is your assigned number)
27. In the Add packet capture blade under Packet capture name input ReswebXA-cap (where X is your assigned number)
28. In the Add packet capture blade under Capture configuration remove the check box for Storage account and check File
29. In the Add packet capture blade under Capture configuration in the Local file path input c:\capture\demo.cap  OK
30. In the Network Watcher – Packet capture blade let the capture run for 30 secs – 1 min then right click on the capture select Stop
31. In the Network Watcher blade under Metric select Network subscription limit
32. In the Network subscription limit blade in the location field select East US 2 from the drop down

* Note here you can see your network consumptions and current limits.