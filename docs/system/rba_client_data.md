# rba\_client\_data

RBA Client Data

[show](#show%20rba_client_data) | [delete](#delete%20rba_client_data) | [add](#add%20rba_client_data)

## show rba\_client\_data

Use this operation to get RBA client data

## Synopsys 

show rba\_client\_data \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the system policys

## delete rba\_client\_data

Use this operation to delete RBA client data

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete rba\_client\_data id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the system policys

This is a mandatory parameter.

## add rba\_client\_data

Use this operation to add RBA client data

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

add rba\_client\_data \[display\_name=&lt;string&gt;\] \[name=&lt;string&gt;\] \[ui\_component=(false | true)\] \[modules=&lt;rba\_module\_client\_data...&gt;\] \[child\_node=&lt;string&gt;\] \[serial\_id=&lt;int&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**display\_name**

parent module display name

**name**

parent module name

**ui\_component**

if its UI component

**modules**

RBA module client data

**child\_node**

This property is for internal use

**serial\_id**

Sequence number
