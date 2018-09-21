# Creating a virtual network in Azure

**Purpose of lab**
  
In this lab you will create a virtual network that will be used to host virtual machines

**Estimated time: 10 min**

1.	In the Azure Dashboard select your Resource Group ResStudentX (where X is your assigned student number).
2.	In the Resource Group blade select Add at the top of the blade.
3.	Select the Windows server 2016 datacenter icon.
*Note you may need to search for the VM gallery item. Input Windows Server 2016 in the search bar.
4.	In the Windows 2016 datacenter blade validate the drop down menu under Select a deployment model is set to Resource Manager --> Create
5.	In the Create a Virtual Machine blade under Resource Group select the drop down menu and select ResStudentX (where X is your student number).
6.	In the Create a Virtual Machine  blade in the Virtual Machine Name Field type ResWebXA  (where X is your student number) in the Name field. 
7.	In the Create a Virtual Machine  blade in the Availablity options use the drop down menu and select Availability Zone
8.	In the Create a Virtual Machine  blade in the Availability Zone section use the drop down menu and select 1.
9.	In the Create a Virtual Machine  blade in the Size field select Change Size
10.	In the Choose a size blade select D2S_V3 Standard  icon.
11.	In the Choose a size blade click the Select icon at the bottom of the blade.
12.	In the Create a Virtual Machine  blade in the User Name Field type StudentX (where X is your student number).
13.	In the Create a Virtual Machine  blade in the Password field and Confirim Password field type P@ssword2018 .
14.	In the Create a Virtual Machine  blade select the Radius button Allow selected ports
15.	In the Create a Virtual Machine  blade in the select inbound ports use the drop down menu and select RDP
16.	In the Create a Virtual Machine  blade select the Radius button Yes in the Save Money section
17.	Check the box to confirm
18.	In the Create a Virtual Machine  blade select Networking from the top menu 
19.	In the Create a Virtual Machine  blade in the Virtual Network section use the drop down men and select StudentX-Vnet1 (where X is your assigned student number). 
20.	In the Create a Virtual Machine  blade in the Subnet section use the drop down men and select StudentX-Sub1 (where X is your assigned student number). 
21.	In the Create a Virtual Machine  blade select Management
22.	In the Create a Virtual Machine  blade in the  Auto-Shutdown section select the Raius button On
23.	In the Time Zone section select Eastern Time (-5 UTC) 
24.	In the Create a Virtual Machine  blade select Review + Create
25.	In the Create a Virtual Machine  blade review your selections click Create
26.	In the Create blade review your settings and select Create 
27.	Close any open blades
28.	From the Azure Dashboard select Create a resource
29.	In the New blade select Compute 
30.	In the Compute blade select Windows Server 2016
31.	In the Create a Virtual Machine blade under Resource Group select the drop down menu and select ResStudentX (where X is your student number).
32.	In the Create a Virtual Machine  blade in the Virtual Machine Name Field type ResWebXB (where X is your student number) in the Name field. 
33.	In the Create a Virtual Machine  blade  in the Region section use the drop down menu and select Japan East
34.	In the Create a Virtual Machine  blade in the User Name Field type StudentX (where X is your student number).
35.	In the Create a Virtual Machine  blade in the Password field and Confirim Password field type P@ssword2018 .
36.	In the Create a Virtual Machine  blade select Review + Create
*note you will get an error because we have a policy that restricts the region
37.	Select the Red exclamation mark
*This will show you the policy that is stopping the deployment
38.	Close the error page
39.	In the Create a Virtual Machine  blade select Basics from the top menu
40.	In the Create a Virtual Machine  blade  in the Region section use the drop down menu and select East US 2
41.	In the Create a Virtual Machine  blade in the Availablity options use the drop down menu and select Availability Zone
42.	In the Create a Virtual Machine  blade in the Availability Zone section use the drop down menu and select 2.
43.	In the Create a Virtual Machine  blade in the Size field select Change Size
44.	In the Choose a size blade select D2S_V3 Standard  icon.
45.	In the Choose a size blade click the Select icon at the bottom of the blade.
46.	In the Create a Virtual Machine  blade select the Radius button Allow selected ports
47.	In the Create a Virtual Machine  blade in the select inbound ports use the drop down menu and select RDP
48.	In the Create a Virtual Machine  blade select the Radius button Yes in the Save Money section
49.	Check the box to confirm
50.	In the Create a Virtual Machine  blade select Networking from the top menu 
51.	In the Create a Virtual Machine  blade in the Virtual Network section use the drop down men and select StudentX-Vnet2 (where X is your assigned student number). 
52.	In the Create a Virtual Machine  blade in the Subnet section use the drop down men and select StudentX-Sub2 (where X is your assigned student number). 
53.	In the Create a Virtual Machine  blade select Management
54.	In the Create a Virtual Machine  blade in the  Auto-Shutdown section select the Raius button On
55.	In the Time Zone section select Eastern Time (-5 UTC) 
56.	In the Create a Virtual Machine  blade select Review + Create
57.	In the Create a Virtual Machine  blade review your selections click Create
58.	Close any open blades



Next Module [Virtual Network Peering](networkpeering.md)