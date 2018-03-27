# rba\_ui

RBA for UI components

[show](#show%20rba_ui) | [delete](#delete%20rba_ui) | [set](#set%20rba_ui) | [add](#add%20rba_ui)

## show rba\_ui

Use this operation to get RBA details for UI components

## Synopsys 

show rba\_ui \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the permission statements

## delete rba\_ui

Use this operation to delete RBA details for UI components(s)

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete rba\_ui id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the permission statements

This is a mandatory parameter.

## set rba\_ui

Use this operation to modify RBA details for UI components

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set rba\_ui id=&lt;string&gt; \[display\_name=&lt;string&gt;\] \[access\_type=(false | true)\] \[name=&lt;string&gt;\] \[parent\_name=&lt;string&gt;\] \[parent\_id=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the permission statements

This is a mandatory parameter.

**display\_name**

UI Component Display Name

**access\_type**

true, if access is allowed

**name**

UI Component Name

**parent\_name**

**parent\_id**

## add rba\_ui

Use this operation to add RBA details for UI components

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add rba\_ui display\_name=&lt;string&gt; name=&lt;string&gt; \[access\_type=(false | true)\] \[parent\_name=&lt;string&gt;\] \[parent\_id=&lt;string&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**display\_name**

UI Component Display Name

This is a mandatory parameter.

**name**

UI Component Name

This is a mandatory parameter.

**access\_type**

true, if access is allowed

**parent\_name**

**parent\_id**