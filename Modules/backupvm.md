8.1	Create a backup vault and backup VM
Site Recovery is a native backup solution that can be utilized to back up content. 
Purpose of lab 
In this lab, we will use Site Recovery to create a backup vault that will be used for Azure backup services. 
Estimated time: 10 minutes 
1.	In the Azure Dashboard select All services 
2.	In the Management Tools section select Recovery Services Vaults
3.	In the Recovery Services Vaults blade select Add
4.	In the Recovery Services Vaults blade input ResStudentX-Vault (where X is your student number) in the Name field. 
5.	In the Recovery Services Vaults under the Resource Group field select the radius button Use existing
6.	In the Recovery Services Vaults under the Resource Group select from the drop down menu ResStudentX (Where X is your student number)
7.	In the Recovery Services Vaults select Pin to dashboard -> Create
8.	In the Azure Dashboard select ResStudentX-Vault (where X is your student number)
9.	In the Recovery Services Vault blade select Backup from the top menu
10.	In the Backup blade in the Where is your workload running select Azure
11.	In the Backup blade in the What do you want to backup select Virtual Machine -> Backup
12.	In the Backup Policy blade under choose backup policy select the drop down menu  Create new
Note: review all the backup options that are available to configure for your Vm
13.	Under policy name input ResXPolicy (where X is your assigned number).  OK
14.	On the Select Virtual machines blade select ReswebXa (where X is your assigned number)  Ok
15.	In the Backup blade select Enable backup
16.	In the Recovery Services Vault blade under Protected items select Backup items
17.	In the Backup Items blade select Azure Virtual machine
*Note: this may take a minute to show up
18.	Select the virtual machine ReswebXb (where X is your assigned number).
19.	In the Backup Items blade select Backup now from the top menu
20.	In the Backup now, blade select Ok
21.	In the Recovery Services Vault blade select Jobs (this will be a few blades back)
22.	In the Recovery Services Vault blade select Backup Jobs
*Note: this will show the history of all backup jobs
23.	Close all blades
