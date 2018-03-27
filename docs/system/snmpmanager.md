# snmpmanager

SNMP Agent Manager configuration

[show](#show%20snmpmanager) | [delete](#delete%20snmpmanager) | [set](#set%20snmpmanager) | [add](#add%20snmpmanager)

## show snmpmanager

Use this operation to get SNMP Manager details

## Synopsys 

show snmpmanager \[snmp\_manager=&lt;internethost&gt;\]

## Parameters 

**snmp\_manager**

Manager IPAddress

## delete snmpmanager

Use this operation to delete SNMP Manager

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete snmpmanager snmp\_manager=&lt;internethost&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**snmp\_manager**

Manager IPAddress

This is a mandatory parameter.

## set snmpmanager

Use this operation to modify SNMP Manager

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set snmpmanager snmp\_manager=&lt;internethost&gt; community=&lt;stringx&gt; \[netmask=&lt;ipaddress&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**snmp\_manager**

Manager IPAddress

This is a mandatory parameter.

**community**

Community Name

This is a mandatory parameter.

**netmask**

Netmask

## add snmpmanager

Use this operation to add SNMP Manager

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add snmpmanager snmp\_manager=&lt;internethost&gt; community=&lt;stringx&gt; \[netmask=&lt;ipaddress&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**snmp\_manager**

Manager IPAddress

This is a mandatory parameter.

**community**

Community Name

This is a mandatory parameter.

**netmask**

Netmask
