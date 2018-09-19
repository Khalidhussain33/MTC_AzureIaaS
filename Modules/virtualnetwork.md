# Creating a virtual network in Azure

**Purpose of lab**
  
In this lab you will create a virtual network that will be used to host virtual machines

**Estimated time: 10 min**

1. In the Azure portal, click Create a resource  Networking > Virtual Network
2. In the Create virtual network blade type StudentX-Vnet1 (where X is your student number) in the Name field.
3. In the Create virtual network blade type 10.X.0.0/16 is listed in the Address Space field (where X is your student number).
4. In the Resource Group field select the drop down menu and select ResStudentX (where X is your student number).
5. In the Create virtual network blade type StudentX-sub1 (where X is your student number) in the Subnet name field.
6. In the Create virtual network blade type 10.X.X.0/24 (where X is your student number) in the Subnet address range field.
7. In the Create virtual network blade select Create.
8. In the Azure Dashboard select your Resource Group ResStudentX (where X is your assigned. student number)
9. In the Resource Group blade select Add from the top menu In the Everything Blade select Virtual Network (Note you may need to search for Virtual Network in the search box at the top)
10. In the Create virtual network blade type StudentX-Vnet2 (where X is your student number) in the name field.
11. In the Address space field input 172.X.0.0/16
12. In the Resource Group field select the drop down menu and select ResStudentX (where X is your student number).
13. In the Subnet Name field input StudentX-sub2 (where X is your student number).
14. In the Subnet address range input 172.X.X.0/24
15. In the Create virtual network blade  Create
16. Close any open blades
17. In the Azure Dashboard select your Resource Group ResStudentX (where X is your assigned. student number)
18. In the Resource Group from the Overview menu select StudentX-Vnet2 (where X is your assigned number).
19. In the virtual network blade select Activity Logs
20. In the Activity Log select Create or Update Virtual Network

![alt text](/Images/azureactivitylogs.png "Azure Activity Logs")

* Note the Azure Activity Logs audit the service actions like creating networks, VMs, etc.

21. Select the JSON tab in the lower portion of the browser

* Note this show the Json code that is used to perform that task, this code could be used to create a template in the future.

22. Close all blades


Next Module [Virtual Network Peering](networkpeering.md)