# Creating and Managing a Resource Group #

Resource Groups are ways to logically group various Azure resource.  They can provide a billing boundary, delegation boundary, and can be used in various ways.

**Purpose of lab:**
  
In this lab you will create a Resource Group that will be utilized throughout this workshop.

**Estimated time:  10 minutes**

1. Launch Internet Explorer (or your browser of choice).

2. In the URL box, type https://portal.azure.com
3. Logon with your supplied credentials.
4. In the Azure Portal select **All Services** from the menu on the left Scroll around and see the various options you can select
5. In the context menu under General select **Resource Group**.
6. At the top of the Resource Group blade select **Add**.
7. In the Create an empty resource group blade type ResStudentX (where X is your assigned student number) in the Resource group name field.
8. In the Create an empty resource group blade select the drop down menu for Resource Group location and select East US 2   **Create**
9. In the Resource Group blade select ResStudentX (Where x is your assigned student number).
10. In the Resource Group Settings blade select **Access Control (IAM)**.
11. In the Access Control (IAM) blade select **Add** from the top menu
12. In the Add Permissions blade in the select the drop down menu in the **Select a role field** (look at all the role options) and select **Contributor**.
13. In the Add Permissions blade in the select menu input DelegateLab and select the DelegateLab group. *Note this group has been precreated for you
14. In the Add Permissions blade click **Save**.
15. Close the IAM blade by selecting the **X** in the top right
16. In the Resource Group Settings blade select **Tags**.
17. In the Resource Group Tags blade type **ResstudentX** (where X is your assigned student number) in left input box (Name).
18. In the Resource Group Tags blade type **SXProjectX** (where X is your student number) in right input box (Value).
19. In the Resource Group Tags blade select **Save** Tags can be created for various reasons to classify assets within a Resource Group
20. In the Resource Group blade select **Overview**
21. In the top right of the Resource Group blade select the pin icon to pin the Resource Group to the dashboard.
22. In the Resource Group blade select **Policies**
23. In the Policies blade select **Assign Policy**
24. In the Assign Policy blade select the box to the right [… ] under the policy definition section 

*Note you should now see 69+ policies

25. In the Available Definitions blade select **Allowed Locations** under the policy definitions  Select
  
*Note you can use the search field in the top right to filter the list

26. In the Assignment Name field input **ResStudentX-East2US-Policy** (where X is your student number) 

*Note: You just created a policy on the resource group to restrict all deployments to the East US 2 Azure region

27. In the Assign Policy blade select the drop down menu under the **Allowed Locations** menu

28. In the Allowed Locations menu select **East US 2**

29. In the Assign Policy blade select **Assign**

30. Close all open blades


Next Module [Create a Virtual Network](virtualnetwork.md)
