# Navigating virtual machine properties

After a virtual machine has been created, a number of additional capabilities are available to the virtual machine owner.

**Purpose of lab**

In this lab, you will view a number of virtual machine properties, make some configuration changes, create a CPU monitor, and navigate through various virtual machine properties.

**Estimated time: 15 min**

1. In the Azure Dashboard select your Resource Group ResStudentX (where X is your assigned student number).
2. In the  Resource group blade select the Vm object  ResWebXA (where X is your student number).
3. In the ResWebXA Settings blade select Activity logs.
4. In the Active log blade review any audit logs that exist.
5. In the ResWebXA Settings blade under the settings section select Properties.
Here you can see the IP address of your virtual machine and various other information
6. In the ResWebXA Settings blade under the MONITOR section select Alert.
7. In the Alert blade select Add metric alert at the top of the blade.
8. In the Add rule blade type CPU in the Name field.
9. In the Add rule blade type “Monitor CPU usage” in the Description field.
10. In the Add rule blade select the drop down menu below the Metric field and select Percentage CPU 
11. In the Threshold field enter 15
12. In the period field, leave it as “Over the last 5 minutes”  OK
13. In the ResWebXA Settings blade select Tags.
14. In the Tags blade select the drop down arrow in the Name field and select ResstudentX (where X is your student number).
15. In the Tags blade select the drop down arrow in the Value field SXProjectX(where x is your student number) --> Save

* Tags can be used for various reason like billing, categorization, etc.

16. In the ResWebXA Properties blade select Networking under the Settings section.

* Note: Here you can see the public IP (if present) and the private Ip of the virtual machine and the firewall rules on the interface

17. In the  Networking blade select the network interface name to the right of Network interface.
18. In the  Network interfaces blade select Ip Configuration under Settings
19. In the Ip Configuration blade select ipconfig1
20. In the Ipconfig blade select static under private IP  Save

* Note here we can remove any public IP address as well, if you remove the public address the only way to connect or manage the machine will be from the private network.

21. Close 2 blades ( this will put you back to the virtual machine blade)
22. In the ResWebXA Settings blade select Extensions  Add
23. In the New resource blade select Network Watcher Agent for Windows  Create
24. In the Install extension blade  OK
25. In the ResWebXA Settings blade select Disks 
26. In the Disks blade select Add data disk
27. In the Disks blade select the drop down menu under the Name field  Create disk
28. In the Create managed disk blade in the name field input ResWebXA-data (where X is your student number) 
29. In the Create managed disk blade under Account Type select the drop down menu and  select Standard (HDD)

* Note as the bottom the estimated performance changes per the disk type

30.	In the Create managed disk blade select Create
31. Repeat steps 27-31 only changing the disk name to ResWebXA-data2 (where X is your student number)
32. In the Create managed disk blade select Save 
33. In the ResWebXA Settings blade below the monitoring section select Diagram

* Note this breaks down the piece of the virtual machine to provide an overview of the configuration

34. In the ResWebXA Settings blade below monitoring select Advisor Recommendations

* Note this will show any configuration recommendations like the VM is not being backuped etc.

35. In the ResWebXA Settings blade select Overview
36. In the virtual machine blade select the pin icon next to CPU,Network,Disk bytes, and Disk operations/sec

* Note: this will pin the VM performance metrics to the Azure dashboard

37. In the ResWebXA Settings blade under  Support and Troubleshooting section select Serial Console

* Note: Azure has serial console access in preview for Linux and Windows machines, this will allow you to have access to your VM during a reboot cycle and troubleshoot the VM.

38. In the console windows type CMD *enter*
39. In the console window type “Restart” *enter*

* Note: this will reboot your vm

40. After the VM restarts in the console window type “CMD” *enter*
41. In the console window type “help”  
This will list your available commands
42. In the console window type “id”
43. Close all blades.
