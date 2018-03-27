# nsgslbservice

NetScaler GSLB Service

[show](#show%20nsgslbservice) | [delete](#delete%20nsgslbservice) | [set](#set%20nsgslbservice) | [add](#add%20nsgslbservice)

## show nsgslbservice

Use this operation to get NetScaler GSLB Service

## Synopsys 

show nsgslbservice \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the NetScaler GSLB Service

## delete nsgslbservice

Use this operation to delete NetScaler GSLB Service

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete nsgslbservice id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the NetScaler GSLB Service

This is a mandatory parameter.

## set nsgslbservice

Use this operation to modify NetScaler GSLB Service

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set nsgslbservice id=&lt;string&gt; \[sites=&lt;string&gt;\] \[tenant=&lt;string&gt;\] \[password=&lt;stringx&gt;\] \[fqdn=&lt;string&gt;\] \[siteList=&lt;string...&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the NetScaler GSLB Service

This is a mandatory parameter.

**sites**

List of sites

**tenant**

Tenant Name

**password**

The pass-phrase that was used to encrypt the private-key.

**fqdn**

Domain Name

**siteList**

List of sites

## add nsgslbservice

Use this operation to add NetScaler GSLB Service

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add nsgslbservice fqdn=&lt;string&gt; siteList=&lt;string...&gt; \[sites=&lt;string&gt;\] \[tenant=&lt;string&gt;\] \[password=&lt;stringx&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**fqdn**

Domain Name

This is a mandatory parameter.

**siteList**

List of sites

This is a mandatory parameter.

**sites**

List of sites

**tenant**

Tenant Name

**password**

The pass-phrase that was used to encrypt the private-key.
