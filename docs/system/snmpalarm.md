# snmpalarm

SNMP Alarm Configurations

[show](#show%20snmpalarm) | [set](#set%20snmpalarm)

## show snmpalarm

Use this operation to get snmp alarm configuration

## Synopsys 

show snmpalarm \[name=&lt;string&gt;\]

## Parameters 

**name**

Alarm Name

## set snmpalarm

Use this operation to modify snmp alarm configuration

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

set snmpalarm \[time=&lt;int&gt;\] \[clear\_alarm\_oid=&lt;int&gt;\] \[name=&lt;string&gt;\] \[enable=(false | true)\] \[severity=&lt;string&gt;\] \[threshold=&lt;int&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**time**

Frequency of the alarm

**clear\_alarm\_oid**

Clear alarm Oid

**name**

Alarm Name

**enable**

Enable Alarm

**severity**

Alarm severity. Supported values: Critical, Major, Minor, Warning, Informational

**threshold**

Threshold Value for the alarm
