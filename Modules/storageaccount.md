# Create Storage Account

Azure storage accounts can be used for a number of capabilities backups, files shares, etc

**Purpose of lab**

In this lab is to create a storage account that will be used to store the NSG flow logs later used in the Traffic analytics tool.

**Estimated time: 15 minutes**

1. In the Azure Portal select All Services from the menu on the left
2. Under Storage select Storage Accounts
3. In Storage Accounts select Add 
4. In the Create storage account blade in the name field input studentXflowlog (where X is your student account).
5. Under the account kind select the drop down and select StorageV2 (general purposed V2)
6. Under the Replication select the drop down and select LRS
7. Under Resource Groups select Use existing 
8. Under Resource Groups select the drop down and select ResStudentX (where X is your assigned student number).
9. In the Create storage account blade validate East US 2 is selected for the location
10. In the Create storage account blade select Create

Next Module [Traffic Analytics](Modules/trafficanalytics.md)