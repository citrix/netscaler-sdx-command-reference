# tenant

Tenants

[show](#show%20tenant) | [delete](#delete%20tenant) | [set](#set%20tenant) | [add](#add%20tenant)

## show tenant

Use this operation to get tenants.

## Synopsys 

show tenant \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the Tenants

## delete tenant

Use this operation to delete a tenant.

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete tenant id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the Tenants

This is a mandatory parameter.

## set tenant

Use this operation to modify a tenant.

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set tenant id=&lt;string&gt; \[user\_name=&lt;string&gt;\] \[system\_resource=&lt;tenant\_system\_resource&gt;\] \[name=&lt;string&gt;\] \[company\_info=&lt;tenant\_company\_info&gt;\] \[password=&lt;stringx&gt;\] \[preauthtoken=&lt;string&gt;\] \[parent\_id=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the Tenants

This is a mandatory parameter.

**user\_name**

User Name for tenant

**system\_resource**

Tenant System Resource

**name**

Name of the Tenant

**company\_info**

Tenant Company Information

**password**

Password

**preauthtoken**

Preauth token for a tenant

**parent\_id**

Tenant ID of the parent Tenant.

## add tenant

Use this operation to add a tenant.

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add tenant user\_name=&lt;string&gt; password=&lt;stringx&gt; parent\_id=&lt;string&gt; \[system\_resource=&lt;tenant\_system\_resource&gt;\] \[name=&lt;string&gt;\] \[company\_info=&lt;tenant\_company\_info&gt;\] \[preauthtoken=&lt;string&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**user\_name**

User Name for tenant

This is a mandatory parameter.

**password**

Password

This is a mandatory parameter.

**parent\_id**

Tenant ID of the parent Tenant.

This is a mandatory parameter.

**system\_resource**

Tenant System Resource

**name**

Name of the Tenant

**company\_info**

Tenant Company Information

**preauthtoken**

Preauth token for a tenant
