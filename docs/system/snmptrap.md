# snmptrap

SNMP Trap Destinations

[show](#show%20snmptrap) | [delete](#delete%20snmptrap) | [set](#set%20snmptrap) | [add](#add%20snmptrap)

## show snmptrap

Use this operation to get snmp trap destination details

## Synopsys 

show snmptrap \[dest\_server=&lt;internethost&gt;\]

## Parameters 

**dest\_server**

Trap Destination Server Address

## delete snmptrap

Use this operation to delete snmp trap destination

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete snmptrap dest\_server=&lt;internethost&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**dest\_server**

Trap Destination Server Address

This is a mandatory parameter.

## set snmptrap

Use this operation to modify snmp trap destination

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set snmptrap dest\_server=&lt;internethost&gt; \[user\_name=&lt;string...&gt;\] \[community=&lt;stringx&gt;\] \[dest\_port=&lt;int&gt;\] \[version=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**dest\_server**

Trap Destination Server Address

This is a mandatory parameter.

**user\_name**

Name of SNMP Trap User

**community**

Community Name

**dest\_port**

Destination Port

**version**

SNMP version

## add snmptrap

Use this operation to add snmp trap destination

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add snmptrap dest\_server=&lt;internethost&gt; \[user\_name=&lt;string...&gt;\] \[community=&lt;stringx&gt;\] \[dest\_port=&lt;int&gt;\] \[version=&lt;string&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**dest\_server**

Trap Destination Server Address

This is a mandatory parameter.

**user\_name**

Name of SNMP Trap User

**community**

Community Name

**dest\_port**

Destination Port

**version**

SNMP version
