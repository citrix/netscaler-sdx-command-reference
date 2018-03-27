# smsprofile

SMS profile

[show](#show%20smsprofile) | [delete](#delete%20smsprofile) | [set](#set%20smsprofile) | [add](#add%20smsprofile)

## show smsprofile

Use this operation to get sms profile.

## Synopsys 

show smsprofile \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the sms profile.

## delete smsprofile

Use this operation to delete sms profile.

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete smsprofile id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the sms profile.

This is a mandatory parameter.

## set smsprofile

Use this operation to modify sms profile.

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set smsprofile id=&lt;string&gt; \[to\_list=&lt;string&gt;\] \[server\_name=&lt;string&gt;\] \[profile\_name=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the sms profile.

This is a mandatory parameter.

**to\_list**

To list.

**server\_name**

SMS server name

**profile\_name**

Profile name for the sms setting.

## add smsprofile

Use this operation to add sms profile.

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add smsprofile to\_list=&lt;string&gt; server\_name=&lt;string&gt; profile\_name=&lt;string&gt;

## Parameters {#parameters-3 style="margin-left: 20px;"}

**to\_list**

To list.

This is a mandatory parameter.

**server\_name**

SMS server name

This is a mandatory parameter.

**profile\_name**

Profile name for the sms setting.

This is a mandatory parameter.
