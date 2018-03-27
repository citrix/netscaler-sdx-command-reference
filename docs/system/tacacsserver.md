# tacacsserver

TACACS Server configuration

[show](#show%20tacacsserver) | [delete](#delete%20tacacsserver) | [set](#set%20tacacsserver) | [add](#add%20tacacsserver)

## show tacacsserver

Use this operation to get TACACS server details

## Synopsys 

show tacacsserver \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the TACACS servers

## delete tacacsserver

Use this operation to delete TACACS server

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete tacacsserver id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the TACACS servers

This is a mandatory parameter.

## set tacacsserver

Use this operation to modify TACACS server

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set tacacsserver id=&lt;string&gt; ip\_address=&lt;ipaddress&gt; name=&lt;string&gt; \[port=&lt;int&gt;\] \[tacacs\_key=&lt;stringx&gt;\] \[auth\_timeout=&lt;int&gt;\] \[accounting=(false | true)\] \[address\_type=&lt;int&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the TACACS servers

This is a mandatory parameter.

**ip\_address**

IP Address of TACACS server

This is a mandatory parameter.

**name**

Name of TACACS server

This is a mandatory parameter.

**port**

port number of TACACS server

**tacacs\_key**

Key shared between the TACACS+ server and clients

**auth\_timeout**

The maximum number of seconds the system will wait for a response from the TACACS server

**accounting**

Enable accounting in the tacacs server

**address\_type**

Configuration Type. Values: 0: IPv4, 1: IPv6

## add tacacsserver

Use this operation to add TACACS server

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add tacacsserver ip\_address=&lt;ipaddress&gt; tacacs\_key=&lt;stringx&gt; name=&lt;string&gt; \[port=&lt;int&gt;\] \[auth\_timeout=&lt;int&gt;\] \[accounting=(false | true)\] \[address\_type=&lt;int&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**ip\_address**

IP Address of TACACS server

This is a mandatory parameter.

**tacacs\_key**

Key shared between the TACACS+ server and clients

This is a mandatory parameter.

**name**

Name of TACACS server

This is a mandatory parameter.

**port**

port number of TACACS server

**auth\_timeout**

The maximum number of seconds the system will wait for a response from the TACACS server

**accounting**

Enable accounting in the tacacs server

**address\_type**

Configuration Type. Values: 0: IPv4, 1: IPv6
