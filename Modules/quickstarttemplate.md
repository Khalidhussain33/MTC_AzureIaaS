# Deploy a VM from a QuickStart template

After a virtual machine has been created on the Azure platform, an admin will need ways to manage and work with that virtual machine.

**Purpose of lab**

In this lab, you connect to your virtual machine via RDP and manage the virtual machine.  

*Note: You must complete the previous lab before you perform this lab.*

**Estimated time: 15 minutes**

1. On your desktop open a new browsers tab and input the URL below
https://github.com/Azure/azure-quickstart-templates/tree/master/anti-malware-extension-windows-vm

2. From your browser select the Deploy to Azure button
3. In the Template blade in the Resource group section select radius button “Use existing” 
4. In drop, down menu of the Resource group section selects your resource group ResStudentX (where X is your student number).
5. In the Template blade in the Public Ip  Address name input “ResTempwkX”) (where X is your student number).
6. In the Template blade in the “Vm name” field input “ResTempX” (where X is your student number).
7. In the Template blade in “VM Size” field input  Standard_DS2_v2
8. In the Template blade in the “Admin Username” input “StudentX” (where X is your student number).
9. In the Template blade in the “Admin Password” field input P@ssword2018
10. In the Template blade in the “Virtual network Name” field input ResStudentX-Vnet3 (where X is your student number).
11. In the Template blade in “Address Prefix” field change the address to 192.X.0.0/16 (where X is your student number).
12. In the Template blade in “SubnetName” field input ResX-sub1 (where X is your student name)
13. In the Template blade in “Subnet1 Prefix” field input 192.X.X.0/24 (where X is your student number).
14. In the Template blade in “Nic Name” field in resstudentX-nic1 (where X is your student number).
15. In the Template blade in “Vm extension” field input anti-malware
16. In the Template blade in “location” input East US 2
17. In the Template blade under terms and conditions check the box “I agree to the terms and conditions stated above”  Purchase

* Note we pulled a template from the gallery and with a single click deployment a virtual machine and the virtual network

Next Module [Navigating VM Properties](Modules/vmproperties.md)