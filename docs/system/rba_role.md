# rba\_role

RBA Role

[show](#show%20rba_role) | [delete](#delete%20rba_role) | [set](#set%20rba_role) | [add](#add%20rba_role)

## show rba\_role

Use this operation to get RBA roles

## Synopsys 

show rba\_role \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the RBA roles

## delete rba\_role

Use this operation to delete RBA role(s)

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete rba\_role id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the RBA roles

This is a mandatory parameter.

## set rba\_role

Use this operation to modify RBA role

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set rba\_role id=&lt;string&gt; \[description=&lt;string&gt;\] \[name=&lt;string&gt;\] \[resourcegroups=&lt;string...&gt;\] \[policies=&lt;string...&gt;\] \[groups=&lt;string...&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the RBA roles

This is a mandatory parameter.

**description**

Description of Role

**name**

Role Name

**resourcegroups**

Resourcegroups attached to this role.

**policies**

Policies attached to this role.

**groups**

Groups to which this role is assigned

## add rba\_role

Use this operation to add RBA role

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add rba\_role name=&lt;string&gt; \[description=&lt;string&gt;\] \[resourcegroups=&lt;string...&gt;\] \[policies=&lt;string...&gt;\] \[groups=&lt;string...&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**name**

Role Name

This is a mandatory parameter.

**description**

Description of Role

**resourcegroups**

Resourcegroups attached to this role.

**policies**

Policies attached to this role.

**groups**

Groups to which this role is assigned
