# prunepolicy

Prune Policy

[show](#show%20prunepolicy) | [set](#set%20prunepolicy)

## show prunepolicy

Use this operation to get the prune policy to view number of days data to retain

## Synopsys 

show prunepolicy \[policy\_name=&lt;string&gt;\]

## Parameters 

**policy\_name**

Policy Name

## set prunepolicy

Use this operation to modify the number of days data to retain

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

set prunepolicy data\_to\_keep\_in\_days=&lt;int&gt; \[policy\_name=&lt;string&gt;\] \[do\_auto\_purge=(false | true)\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**data\_to\_keep\_in\_days**

Number of days data to retain

This is a mandatory parameter.

**policy\_name**

Policy Name

**do\_auto\_purge**

True, if user wants to opt for auto DB data purging once disk usage reaches threshold value
