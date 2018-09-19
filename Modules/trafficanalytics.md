5.1	Traffic Analytics
Traffic analysis is a new capability that uses the NSG flog logs to visualize and network flow in Azure.
Purpose of lab
The purpose of this lab is you show you how to enable Traffic analysis for your organization and start to visualize azure traffic.
Estimated time:15 min
1.	In the Azure Portal select All Services from the menu on the left
2.	 In the context menu under the networking section select Network Watcher
3.	 In the Network Watcher blade select NSG flow logs
4.	 In the middle pane select ResWebXA-NSG (where X is your student number)
5.	 In the Flow log settings under status select On
6.	 In the Flow log settings under storage account select the drop down studentXflowlog (where X is your student number)
7.	  In the Flow log settings under Retention days input 20
8.	In the Flow log settings under Traffic Analytics status select On
9.	 In the Flow log settings under OMS workspace select MTCLab
10.	In the Flow log settings select Save 
11.	Repeat steps 5- 10 for ResWebXB-NSG (where X is your student number)
12.	In the Network Watcher blade select Traffic Analytics
*Note: this could take up to 5-10 minutes to generate view etc.. move onto lab 5.2 and return back *
13.	Select the map picture near Traffic distribution across datacenters
14.	On the map you will see a green check box showing the datacenters your services are deployed in select the green check box
15.	On the Popup window select more details at the bottom
16.	Under Azure DCs communicating with East 2 select “see more”
17.	*Note this bring up the Kusto query lang and lets you do deep analysis
18.	Close all blades
