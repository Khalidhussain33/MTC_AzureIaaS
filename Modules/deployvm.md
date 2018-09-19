3.1	Deploying virtual machines to your Azure networks 
Purpose of lab
In this lab, you will deploy two virtual machines into a Resource Group and deploy them to an Azure network.
Estimated time: 15 minutes 
1.	In the Azure Dashboard select your Resource Group ResStudentX (where X is your assigned student number).
2.	In the Resource Group blade select Add at the top of the blade.
3.	Select the Windows server 2016 datacenter icon.
*Note you may need to search for the VM gallery item. Input Windows Server 2016 in the search bar.
4.	In the Windows 2016 datacenter blade validate the drop down menu under Select a deployment model is set to Resource Manager --> Create
5.	In the Create a Virtual Machine blade under Resource Group select the drop down menu and select ResStudentX (where X is your student number).
6.	In the Create a Virtual Machine  blade in the Virtual Machine Name Field type ResWebXA  (where X is your student number) in the Name field. 
7.	In the Create a Virtual Machine  blade in the Size field select Change Size
8.	In the Choose a size blade select D2S_V3 Standard  icon.
9.	In the Choose a size blade click the Select icon at the bottom of the blade.
10.	In the Create a Virtual Machine  blade in the User Name Field type StudentX (where X is your student number).
11.	In the Create a Virtual Machine  blade in the Password field and Confirim Password field type P@ssword2018 .
12.	In the Create a Virtual Machine  blade Under Inbound Port rules
13.	In the Basics blade validate the Location field is set to East US 2. 
14.	 In the Basics blade select Yes under the Save Money section and check the I confirm box
15.	In the Basics blade click OK.
16.	In the Choose a size blade select D2S_V3 Standard  icon.
17.	In the Settings blade under availability Zone select the drop down menu and select Zone 1
*Note an AZ protects against datacenter failure in a single Azure region*
18.	In the Settings blade select Virtual network  StudentX-Vnet1 (where X is your assigned student number). 
19.	In the Settings blade select the drop down menu under “select public inbound ports” and choose RDP 3389
20.	In the Settings blade select under Auto-shutdown select ON
21.	In the Settings blade select Eastern Time (-5 UTC) under the Shutdown time
22.	In the Settings blade click OK
23.	In the Summary blade review your selections click OK
24.	In the Create blade review your settings and select Create 
25.	From the Azure Dashboard select Create a resource
26.	In the New blade select Compute 
27.	In the Compute blade select Windows Server 2016
28.	In the Basics blade in the Name field type ResWebXB (where X is your student number) . 
29.	In the Basics blade in the Vm disk type select HDD from the drop down menu
30.	In the Basics blade in the User Name field type StudentX (where X is your student number) in the User name field. 
31.	In the Basics blade in the Password field type P@ssword2018 .
32.	Select the Radius button Use existing below the Resource Group field.
33.	Select the drop down menu and select ResStudentX (Where X is your student number).
34.	In the Basics blade under Location select Japan East
35.	In the Basics blade select Yes under the Save Money section and check the I confirm box
36.	In the Basics blade select Ok
37.	 In the Choose a size blade select D2S_V3 Standard  icon.
38.	 In the Choose a size blade click Select icon at the bottom of the screen.
39.	In the Settings blade select the drop down menu under “select public inbound ports” and choose RDP 3389
40.	In the Settings blade select under Auto-shutdown select ON
41.	In the Settings blade select Eastern Time (-5 UTC) under the Shutdown time
42.	In the Settings blade select OK
*Note you should get an error stating the deployment was disallowed by policy, this is because we tried to create a VM in Japan East and the policy only allow the VM to be located in East US 2
43.	In the Create virtual machine blade select step 1
44.	Change the location to East US 2  OK
45.	In the Choose a size blade select D2S_V3 Standard  icon  Select
46.	In the Settings blade under availability Zone select the drop down menu and select Zone 2

47.	In the Settings blade select Virtual network  StudentX-Vnet2
48.	In the Settings blade select Extensions  Add Extension
49.	Select Microsoft Antimalware   Create
50.	In the Install extension blade select OK
51.	In the  extension blade select OK
52.	In the Settings blade select the drop down menu under “select public inbound ports” and choose RDP 3389
53.	In the Settings blade select under Auto-shutdown select ON
54.	In the Settings blade select Eastern Time (UTC -5) under the Shutdown time
55.	In the Settings blade select OK
56.	In the Create blade review your selections click Create
