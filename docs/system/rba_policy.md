# rba\_policy

RBA Policy

[show](#show%20rba_policy) | [delete](#delete%20rba_policy) | [set](#set%20rba_policy) | [add](#add%20rba_policy)

## show rba\_policy

Use this operation to get system policies

## Synopsys 

show rba\_policy \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the system policys

## delete rba\_policy

Use this operation to delete system policy(s)

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete rba\_policy id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the system policys

This is a mandatory parameter.

## set rba\_policy

Use this operation to modify system policy

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set rba\_policy id=&lt;string&gt; \[ui=&lt;rba\_ui...&gt;\] \[statement=&lt;rba\_statement...&gt;\] \[description=&lt;string&gt;\] \[name=&lt;string&gt;\] \[roles=&lt;string...&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the system policys

This is a mandatory parameter.

**ui**

RBA for UI components

**statement**

RBA statement

**description**

Description of Policy

**name**

Policy Name

**roles**

Roles to which this policy attached

## add rba\_policy

Use this operation to add system policy

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add rba\_policy name=&lt;string&gt; \[ui=&lt;rba\_ui...&gt;\] \[statement=&lt;rba\_statement...&gt;\] \[description=&lt;string&gt;\] \[roles=&lt;string...&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**name**

Policy Name

This is a mandatory parameter.

**ui**

RBA for UI components

**statement**

RBA statement

**description**

Description of Policy

**roles**

Roles to which this policy attached
