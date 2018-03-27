# rba\_statement

RBA Statement

[show](#show%20rba_statement) | [delete](#delete%20rba_statement) | [set](#set%20rba_statement) | [add](#add%20rba_statement)

## show rba\_statement

Use this operation to get RBA statements

## Synopsys 

show rba\_statement \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the permission statements

## delete rba\_statement

Use this operation to delete RBA statement(s)

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete rba\_statement id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the permission statements

This is a mandatory parameter.

## set rba\_statement

Use this operation to modify RBA statement

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set rba\_statement id=&lt;string&gt; \[dependent\_resources=&lt;string&gt;\] \[operation\_name=&lt;string&gt;\] \[access\_type=(false | true)\] \[resource\_type=&lt;string&gt;\] \[parent\_name=&lt;string&gt;\] \[parent\_id=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the permission statements

This is a mandatory parameter.

**dependent\_resources**

Dependent Resources

**operation\_name**

Operation Name

**access\_type**

true, if access is allowed

**resource\_type**

Resource Type

**parent\_name**

**parent\_id**

## add rba\_statement

Use this operation to add RBA statement

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add rba\_statement dependent\_resources=&lt;string&gt; operation\_name=&lt;string&gt; resource\_type=&lt;string&gt; \[access\_type=(false | true)\] \[parent\_name=&lt;string&gt;\] \[parent\_id=&lt;string&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**dependent\_resources**

Dependent Resources

This is a mandatory parameter.

**operation\_name**

Operation Name

This is a mandatory parameter.

**resource\_type**

Resource Type

This is a mandatory parameter.

**access\_type**

true, if access is allowed

**parent\_name**

**parent\_id**