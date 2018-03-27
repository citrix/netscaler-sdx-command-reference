# nsvmacs

vmacs for shared vlans

[show](#show%20nsvmacs) | [add](#add%20nsvmacs) | [do custom](#do%20nsvmacs%20custom)

## show nsvmacs

Use this operation to list vmacs generated for all ns or a specific NS

## Synopsys 

show nsvmacs \[ns\_ip\_address=&lt;string&gt;\]

## Parameters 

**ns\_ip\_address**

NetScaler IP Address

## add nsvmacs

Use this operation to generate and add vmacs to a specific NS

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

add nsvmacs ns\_ip\_address=&lt;string&gt; generation\_method=&lt;string&gt; \[vmacs=&lt;string&gt;\] \[base\_vmac=&lt;string&gt;\] \[act\_id=&lt;string&gt;\] \[increment\_by=&lt;int&gt;\] \[vmac\_count=&lt;int&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**ns\_ip\_address**

NetScaler IP Address

This is a mandatory parameter.

**generation\_method**

(MANUAL, BASE or RANDOM)

This is a mandatory parameter.

**vmacs**

Comma Seperated VMac list

**base\_vmac**

Base VMac Address

**act\_id**

Activity Id

**increment\_by**

increment by

**vmac\_count**

increment by

## do nsvmacs custom

Use this operation to reset interface settings

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

do nsvmacs custom \[ns\_ip\_address=&lt;string&gt;\] \[vmacs=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**ns\_ip\_address**

NetScaler IP Address

**vmacs**

Comma Seperated VMac list
