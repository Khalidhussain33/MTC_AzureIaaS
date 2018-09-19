# Connecting to a virtual machine #

After a virtual machine has been created on the Azure platform, an admin will need ways to manage and work with that virtual machine.

**Purpose of lab**

In this lab, you connect to your virtual machine via RDP and manage the virtual machine.

NOTE: You must complete the previous lab before you perform this lab.

**Estimated time: 20 minutes**

1.	In the Azure Dashboard select your Resource Group ResStudentX (where X is your assigned student number).
1. In the Resource group blade select the Vm object ResWebXA (where X is your student number).
2. In the top of the ResWebXA (where X is your student number) blade select Connect.
3. In the connect to virtual machine window select download RDP file
4. In the Internet Explorer open/save dialog select Open.
5. In the Remote desktop connection dialog box, select the Don’t ask me again check box, and then click Connect.
6. In the Windows Security dialog box, select the Use other account check box.
7. In the logon screen, type StudentX and the password P@ssword2018
8. In the Remote desktop connection dialog box, select the Don’t ask me again check box, and then click Yes
9. After logon wait until the Server Manager Admin tool opens
10. From the Server Manager Dashboard select File and Storage Services in the upper left
11. In File and Storage Services select Storage Pools

*Note we added to 2 drives to our Vm now we want to pool them together

12. In the Storage Pools section in the lower right under Physical Disks select TASKS  New Storage Pool
13. In the New storage Pool Wizard  Next
14. In the Specify a storage pool name input ResWebXA-Pool (where X is your student number)  Next
15. In the Select physical disks for the storage pool select both disk  Next
16. In the Confirmation selections  Create
17. In the view results select Create a virtual disk when the wizard closes  close
18. In the Storage Pool windows select Ok
19. In the New virtual disk wizard  Next
20. In the specify the virtual disk name input ResWebXA-DataVolume (where X is your student number)
21. In the specify enclosure resiliency  Next
22. In the Select the storage layout select Simple  Next

*Remember Azure storage is providing the resiliency there is no need to raid the virtual disk as this adds performance penalties

23. In the Specify the provisioning Type  Next
24. In the Specify the size of the virtual disk select Maximum size  Next 
25. In the Confirm selections page select Create
26. On the view results page  Close
27. In the New Volume Wizard select Next
28. In the Select the Server and disk select Next 
29. In the Specify the size of the volume select Next 
30. In the Assign to a drive letter or folder select Next
31. In the select file system settings select the drop down menu next to file system and choose REFS  Next
32. In the Confirm selections select Create
33. In the Completion page select Close

*Note you now have a 2TB volume that can be extended at any time for capacity or performance 

34. Select the Windows start button Rick click on the PowerShell Icon and select More
35. In the more properties select Run as Administrator
36. In the PowerShell windows type:
 Install-WindowsFeature  -Name Web-Server  -IncludeManagementTools

*Note wait until the install has completed before moving to the next step

37. Open Internet Explorer and connect to Aka.ms/mtcworkshop 

*You may need to disable IE enhanced security to download the file

38. In the Azure IaaS folder download Wireshark-win64-2.2.7
39. Once downloaded install WireShark accepting all the defaults
40. After installation completes open Wireshark  File Open
41. Browse to C:\capture\demo.cap

*Note this is the packet capture from the virtual machine that we configured during the network watcher section

39. Close the RPD window

Next Module [Setup and Configure Log Analytics](loganaltyics.md)