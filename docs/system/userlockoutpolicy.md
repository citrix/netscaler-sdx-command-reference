# userlockoutpolicy

User Lockout Policy configuration

[show](#show%20userlockoutpolicy) | [set](#set%20userlockoutpolicy)

## show userlockoutpolicy

Use this operation to get User Lockout Policy details

## Synopsys 

show userlockoutpolicy \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key

## set userlockoutpolicy

Use this operation to modify User Lockout Policy details

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

set userlockoutpolicy \[user\_lockout\_interval=&lt;int&gt;\] \[invalid\_logins=&lt;int&gt;\] \[enable\_user\_lockout=(false | true)\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**user\_lockout\_interval**

User lockout Interval in secoonds

**invalid\_logins**

No of invalid logins for User lockout

**enable\_user\_lockout**

Enable user User lockout feature
