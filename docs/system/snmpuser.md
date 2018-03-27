# snmpuser

SNMP User

[show](#show%20snmpuser) | [delete](#delete%20snmpuser) | [set](#set%20snmpuser) | [add](#add%20snmpuser)

## show snmpuser

Use this operation to get SNMP User details

## Synopsys 

show snmpuser \[name=&lt;string&gt;\]

## Parameters 

**name**

Name of SNMP User

## delete snmpuser

Use this operation to delete SNMP User

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete snmpuser name=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**name**

Name of SNMP User

This is a mandatory parameter.

## set snmpuser

Use this operation to modify SNMP User

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set snmpuser security\_level=&lt;int&gt; name=&lt;string&gt; \[view\_name=&lt;string&gt;\] \[auth\_protocol=&lt;int&gt;\] \[privacy\_protocol=&lt;int&gt;\] \[auth\_password=&lt;stringx&gt;\] \[privacy\_password=&lt;stringx&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**security\_level**

Security Level of SNMP User. Values: 0: noAuthNoPriv, 1: authNoPriv, 2: authPriv

This is a mandatory parameter.

**name**

Name of SNMP User

This is a mandatory parameter.

**view\_name**

SNMP View Name attached to the SNMP User

**auth\_protocol**

Authentication Protocol of SNMP User. Values: 0:noValue, 1: MD5, 2: SHA1

**privacy\_protocol**

Privacy Protocol of SNMP User. Values: 0:noValue, 1: DES, 2: AES

**auth\_password**

Authentication Password of SNMP User

**privacy\_password**

Privacy Password of SNMP User

## add snmpuser

Use this operation to add SNMP User

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add snmpuser security\_level=&lt;int&gt; name=&lt;string&gt; \[view\_name=&lt;string&gt;\] \[auth\_protocol=&lt;int&gt;\] \[privacy\_protocol=&lt;int&gt;\] \[auth\_password=&lt;stringx&gt;\] \[privacy\_password=&lt;stringx&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**security\_level**

Security Level of SNMP User. Values: 0: noAuthNoPriv, 1: authNoPriv, 2: authPriv

This is a mandatory parameter.

**name**

Name of SNMP User

This is a mandatory parameter.

**view\_name**

SNMP View Name attached to the SNMP User

**auth\_protocol**

Authentication Protocol of SNMP User. Values: 0:noValue, 1: MD5, 2: SHA1

**privacy\_protocol**

Privacy Protocol of SNMP User. Values: 0:noValue, 1: DES, 2: AES

**auth\_password**

Authentication Password of SNMP User

**privacy\_password**

Privacy Password of SNMP User
