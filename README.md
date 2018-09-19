# Azure IaaS Workshop #

The purpose of this workshop is to introduce organizations to Microsoft Azure services. This workshop is designed to expose organization to the subset of Azure services that focuses on infrastructure as a service (IAAS).

We assume you have an Azure Subscription... If you don't, break out your Microsoft Account (aka LiveID, Hotmail account, etc) and pick one of these options:

* [Free $200/One Month Trial](https://azure.microsoft.com/en-us/free/) – $200 credit for use in 30 days.
* [Visual Studio Dev Essentials Program](https://www.visualstudio.com/dev-essentials/?campaign=VSBlog_AzureXamAnnoucement_VSDE) – Comes with $25 a month of Azure credit for 12 months.
* [IT Pro Cloud Essentials Program](https://www.microsoft.com/itprocloudessentials/en-US) – Also comes with $25 a month of Azure credit for 12 months.

## Modules 1 - Creating and Managing a Resource Group ##

Resource Groups are ways to logically group various Azure resource.  They can provide a billing boundary, delegation boundary, and can be used in various ways.

* [Creating Resource groups](Modules/resourcegroups.md)

## Modules 2 - Azure Networking ##

With Azure, any user or organization can create a self-contained network and connect into those networks with these methods:
Point-to-site,
Site-to-site,
ExpressRoute

* [Create a Virtual Network](Modules/virtualnetwork.md)
* [Virtual Network Peering](Modules/networkpeering.md)

## Modules 3 - Virtual Machines in Azure ##

One of the services offered by Azure is Infrastructure as a Service (IaaS) this provides the ability to create and manages virtual machines. Microsoft fully supports a wide range of virtual appliances and operating systems.

* [Deploying VM's](Modules/deployvm.md)
* [Using Quickstart Templates](Modules/quickstarttemplate.md)
* [Navigating VM Properties](Modules/vmproperties.md)
* [Create Custom Dashboards](Modules/dashboards.md)
* [Network Security Groups](Modules/netwroksecuritygroups.md)
* [Connecting to a Virtual Machines](Modulesconnectingtovm.md)

## Modules 4 - Azure Storage Accounts ##

Azure storage accounts can be used for a number of capabilities backups, files shares, etc

* [Creating an Azure Storage Accounte](Modules/storageaccount.md)

## Modules 5 - Network Analytics ##

Network watcher is an Azure service that allow you to capture network traffic to an Azure endpoint.  You can trigger this service from an alert and then start to capture network traffic that can then be analyzed by your IT staff.

* [Traffic Analytics](Modules/trafficanalytics.md)
* [Network Watcher](Modules/networkwatcher.md)

## Modules 6 - Securing and Monitoring Azure Resources ##

As assets move to the cloud organization have concerns around security and monitoring. Microsoft Azure had a number of capabilities that can provide organizations a piece of mind knowing their cloud assets are being protected and that they have full insights into those assets.

* [Setup and Configure Log Analytics](Modules/loganaltyics.md)
* [Azure Security Center](Modules/azuresecuritycenter.md)

## Modules 7 - Azure Recovery Services ##

With the Site Recovery service, organizations can use the cloud for a number of recovery services. Azure works with a number of backup solutions to allow you to store backups in the cloud and use the cloud for site recovery with VM replication.

* [Automate Backups for VM's](Modules/backupvmmd.md)

## Contributing ##

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.