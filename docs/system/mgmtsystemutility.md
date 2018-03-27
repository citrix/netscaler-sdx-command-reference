# MgmtSystemUtility

Device generic utility

## add MgmtSystemUtility

Use this operation to perform configuration on multiple ipaddress

## Synopsys 

add MgmtSystemUtility device\_family\_type=&lt;string&gt; resource\_type=&lt;string&gt; payload=&lt;string&gt; ipaddress=&lt;ipaddress...&gt; \[sync=(false | true)\] \[act\_id=&lt;string&gt;\] \[failure\_action=&lt;string&gt;\]

## Parameters 

**device\_family\_type**

Device family type

This is a mandatory parameter.

**resource\_type**

Type of resource

This is a mandatory parameter.

**payload**

Payload/Body Request

This is a mandatory parameter.

**ipaddress**

List of SVM IP Address

This is a mandatory parameter.

**sync**

Ping SVM to check its status

**act\_id**

Activity Id

**failure\_action**

Action taken on failure
