# rba\_resourcegroup

RBA Resource Group

[show](#show%20rba_resourcegroup) | [delete](#delete%20rba_resourcegroup) | [set](#set%20rba_resourcegroup) | [add](#add%20rba_resourcegroup)

## show rba\_resourcegroup

Use this operation to get RBA resource groups

## Synopsys 

show rba\_resourcegroup \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for RBA resource group

## delete rba\_resourcegroup

Use this operation to delete RBA resource groups

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete rba\_resourcegroup id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for RBA resource group

This is a mandatory parameter.

## set rba\_resourcegroup

Use this operation to modify RBA resource groups

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set rba\_resourcegroup id=&lt;string&gt; \[name=&lt;string&gt;\] \[props=&lt;rba\_resourcegroup\_props...&gt;\] \[roles=&lt;string...&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for RBA resource group

This is a mandatory parameter.

**name**

Resource Group Name

**props**

RBA Resource Group Props

**roles**

Roles to which this resourcegroup is assigned

## add rba\_resourcegroup

Use this operation to add RBA resource groups

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add rba\_resourcegroup name=&lt;string&gt; \[props=&lt;rba\_resourcegroup\_props...&gt;\] \[roles=&lt;string...&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**name**

Resource Group Name

This is a mandatory parameter.

**props**

RBA Resource Group Props

**roles**

Roles to which this resourcegroup is assigned
