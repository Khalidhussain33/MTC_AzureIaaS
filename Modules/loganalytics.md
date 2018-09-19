# Setup and Configure Log Analytics

**Purpose of lab**

In this lab, you will setup Azure Log analytics which allow you to monitor systems regardless of their location. OMS can be used to provide a central dashboard for an organization.

**Estimated time: 10 minutes**

1. In the Azure Dashboard select All services from the browse menu select Log Analytics.
2. In the Log Analytics blade select the MTCLab workspace
3. In the Log Analytics blade select  Workspace Summary
4. In the Overview blade select Add at the top of the screen

* Note: Review the solution options select more at the bottom

5. Close the management solutions blade
6. In the Overview blade select System Update assessment

* Note: Review the different views

7. Close the Updates blade
8. In the Overview blade select Security and Audit solution

* Note: review the threats and any active issues

9. Close the security blade
10. In the Overview blade select Analytics in the top menu

* Note:  this opens the Azure log Analytics query view

11. In the Azure log analytics query screen under Common Queries Select “Run” under data volume

* Log analytics can store any log data from Firewalls, to customer application, etc.

12. At the top of the screen Select the + icon to open a new query page
13. In the top right click the folder icon
14. Expand Saved Queries and expand Workshop
15. Double click the workshop query
16. Select the run button

* Review the data returned, log analytics can take in any feeds and you can use the Kusto query lang to create dashboard etc.

17. In the middle pane select Chart
18. If prompted select Yes
19. In the stack column select the drop down menu and choose pie chart
20. Close all blades

Next Module [Azure Security Center](Modules/azuresecuritycenter.md)