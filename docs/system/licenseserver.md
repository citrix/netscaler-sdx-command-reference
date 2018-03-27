# licenseserver

License server information

[show](#show%20licenseserver) | [delete](#delete%20licenseserver) | [set](#set%20licenseserver) | [add](#add%20licenseserver)

## show licenseserver

Use this operation to get License server details

## Synopsys 

show licenseserver \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key

## delete licenseserver

Use this operation to delete License server

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete licenseserver \[id=&lt;string&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key

## set licenseserver

Use this operation to modify License server

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set licenseserver \[connection\_status=(false | true)\] \[grace=(false | true)\] \[port=&lt;int&gt;\] \[id=&lt;string&gt;\] \[grace\_time\_left=&lt;int&gt;\] \[server=&lt;internethost&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**connection\_status**

License server is connected

**grace**

Box is running on grace

**port**

License port

**id**

Id is system generated key

**grace\_time\_left**

grace time remaining left in Hours

**server**

Server/IP address of License server

## add licenseserver

Use this operation to add License server

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add licenseserver \[connection\_status=(false | true)\] \[grace=(false | true)\] \[port=&lt;int&gt;\] \[grace\_time\_left=&lt;int&gt;\] \[server=&lt;internethost&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**connection\_status**

License server is connected

**grace**

Box is running on grace

**port**

License port

**grace\_time\_left**

grace time remaining left in Hours

**server**

Server/IP address of License server
