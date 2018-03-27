# rba\_operation

RBA Operation

[show](#show%20rba_operation) | [delete](#delete%20rba_operation) | [set](#set%20rba_operation) | [add](#add%20rba_operation)

## show rba\_operation

Use this operation to get RBA operations

## Synopsys 

show rba\_operation \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the RBA operations

## delete rba\_operation

Use this operation to delete RBA Operation(s)

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete rba\_operation id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the RBA operations

This is a mandatory parameter.

## set rba\_operation

Use this operation to modify RBA Operations

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set rba\_operation id=&lt;string&gt; \[name=&lt;string&gt;\] \[parent\_name=&lt;string&gt;\] \[parent\_id=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the RBA operations

This is a mandatory parameter.

**name**

Operation Name

**parent\_name**

**parent\_id**

## add rba\_operation

Use this operation to add RBA Operations

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add rba\_operation name=&lt;string&gt; \[parent\_name=&lt;string&gt;\] \[parent\_id=&lt;string&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**name**

Operation Name

This is a mandatory parameter.

**parent\_name**

**parent\_id**