# snmpview

SNMP view

[show](#show%20snmpview) | [delete](#delete%20snmpview) | [set](#set%20snmpview) | [add](#add%20snmpview)

## show snmpview

Use this operation to get SNMP View details

## Synopsys 

show snmpview \[name=&lt;string&gt;\]

## Parameters 

**name**

Name of SNMP view

## delete snmpview

Use this operation to delete SNMP View

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete snmpview name=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**name**

Name of SNMP view

This is a mandatory parameter.

## set snmpview

Use this operation to modify SNMP View

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set snmpview name=&lt;string&gt; \[subtree=&lt;string&gt;\] \[type=(false | true)\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**name**

Name of SNMP view

This is a mandatory parameter.

**subtree**

Subtree associated with the SNMP view

**type**

Include or Exclude the associated subtree . Values. true:Include, false: Exclude

## add snmpview

Use this operation to add SNMP View

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add snmpview name=&lt;string&gt; \[subtree=&lt;string&gt;\] \[type=(false | true)\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**name**

Name of SNMP view

This is a mandatory parameter.

**subtree**

Subtree associated with the SNMP view

**type**

Include or Exclude the associated subtree . Values. true:Include, false: Exclude
