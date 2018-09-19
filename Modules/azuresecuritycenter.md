# Setup and Configure Azure Security Center #

Azure Security Center provides an organization the ability to review the security posture of the certain services running in Azure.

**Purpose of lab**

In this lab, you will configure Azure Security Center and look at the various capabilities that can be enabled

**Estimated time: 10 minutes**

1. In the Azure Dashboard select All services
2. In the Security section select security center
3. In the Security Center blade select Security Policy
4. In the Security Policy blade select the subscription (MTC Azure Workshop 2)
5. In the Security Policy blade under Data Collection review the options
6. In the Security Policy blade under Security policy review the options that can be enabled
7. Close the blade
8. In the Security Policy blade select Overview
9. In the middle pane under Resource security hygiene select Compute and apps
10. In the Compute blade select VMS and Computers

 *Note here you can see Azure VMs and on premises assets

11. Close the compute blade
12. In the Overview blade below, Advanced cloud defense select Just in time access
13. In the Just in time blade select recommended tab
14. In the recommended tab select ResWebXA (Where X is your student number)  Enable JIT on VM
15. On the JIT VM configuration select save
16. In the Azure Dashboard select ResWebXA (where X is your student number)
17. In the virtual machine blade select connect

*Note your connection will fail because JIT creates a default deny rule to block access to the VM and you must request

18. In the Azure Dashboard select more services from the browse menu select security center
19. In the Overview blade below, Advanced cloud defense select Just in time access
20. In the Just in time blade under the configured tab select ResWebXA (Where X is your student number)  Request access
21. In the Request access blade and under the toggle column select On for RDP/3389  Open ports
22. In the Azure Dashboard select ResWebXA (where X is your student number)
23. In the virtual machine blade select connect

*Note you can now connect as the JIT request opened RDP for a time period and then will be disabled.

24. Close all blades

Next Module [Automate Backups for VM's](Modules/backupvm.md)