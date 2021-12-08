# CloudFormationEC2
Create CRDB EC2 instances

This CloudFormation (CF) Template expects that the cf-vpic template has been previously executed.  The outputs from that cf-vpic are used as inputs to this CF Template.

# TODO
1.  create an additional user
2.  create a cert - what am I going to do for other regions?  Can I export and have user copy the export as a parameter?
3.  copy the cert to all following clusters via new user
4.  create node certs
5.  additional copy
6.  create the join on the last instance
7.  have the system start the cluster