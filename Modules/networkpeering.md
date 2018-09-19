# Virtual Network Peering

Virtual network peering allows for a low latent connection between two or more virtual networks in the same Azure Region. If you wish to connect virtual network between regions you must use Express route or a site to site vpn.

**Purpose of lab**

In this lab, is to connect the 2 newly created networks via peering.
  
**Estimated time: 15 minutes**

1. In the Azure Dashboard select your Resource Group ResStudentX (where X is your assigned. student number)
2. In the Resource Group blade select Studentx-Vnet1 
3. In the Virtual network blade select Peerings
4. In the Virtual network Peering blade select Add
5. In the Add peering blade input “PeerV1-V2” in the Name field
6. In the Add peering blade under Virtual network select the drop down menu select StudentX-Vnet2 (where X is your assigned student number).
7. In the Add peering blade select Ok
8. In the Virtual network Peering blade close the peering properties by select X in the top corner
9. In the Resource Group blade select Studentx-Vnet2
10. In the Virtual network blade select Peerings
11. In the Virtual network Peering blade select Add
12. In the Add peering blade input “PeerV2-V1” in the Name field
13. In the Add peering blade under Virtual network select the drop down menu select StudentX-Vnet1 (where X is your assigned student number).
14. In the Add peering blade select Ok

* Note: It might take a second, but the screen should update the peering status to connected

15. Close all open blade


Next Module [Deploying VM's](Modules/deployvm.md)