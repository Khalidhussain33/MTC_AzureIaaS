# Network Security Groups

Organizations have various methods that they use to secure IT resources, Azure provides a number of capabilities like Network Security Groups (NSGs).  NSGs can be used to create firewall rules on subnets, virtual machines, and resource groups.

**Purpose of lab**

In this lab, you will configure NSG policies to allow port 80 inbound to your virtual machines.

**Estimated time: 10 minutes**

1. In the Azure Portal select All services  from the menu on the left
2. In the browse menu select Network Security Groups from the Networking section.
3. In the Network Security Group blade select ResWebXA-nsg (where X is your student number).
4. In the Settings blade select Inbound security rules.
5. In the Inbound security rules blade select Add from the top of the blade.
6. In the Add inbound security rules blade select basic in the top left
7. In the Add inbound security rules blade use the Service drop down and select HTTP.
8. In the Add inbound security rules blade type AllowHTTP in the Name field then click ADD
9. In the Inbound security rules blade validate the new rule has been created.
10. Close the Inbound security rules blade selecting the X in the top right.
11. In the Network Security Group blade select ResWebXB (where X is your student number).
12. In the Settings blade select Inbound security rules.
13. In the Inbound security rules blade select Add from the top of the blade.
14. In the Add inbound security rules blade in the Destination port range input port 80
15. In the Add inbound security rules blade type AllowHTTP in the Name field.
16. In the Add inbound security rules blade select Allow Action section then click Add.
17. In the Inbound security rules blade validate the new rule has been created.
18. close all the blades

Next Module [Creating an Azure Storage Account](Modules/storageaccount.md)