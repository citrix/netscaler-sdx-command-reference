# aaaserver

AAA Server configuration

[show](#show%20aaaserver) | [set](#set%20aaaserver)

## show aaaserver

Use this operation to get AAA server details

## Synopsys 

show aaaserver \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the servers

## set aaaserver

Use this operation to modify AAA server details

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

set aaaserver primary\_server\_type=&lt;string&gt; \[fallback\_local\_authentication=(false | true)\] \[external\_servers=&lt;external\_server...&gt;\] \[primary\_server\_name=&lt;string&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**primary\_server\_type**

Type of primary server. Supported types 1. LOCAL 2.RADIUS 3.LDAP 4.TACACS 5.KEYSTONE

This is a mandatory parameter.

**fallback\_local\_authentication**

Enable local fallback authentication

**external\_servers**

List of external servers

**primary\_server\_name**

Name of primary server name
