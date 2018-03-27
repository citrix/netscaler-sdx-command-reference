# fipspartition

HSM FIPS Partition

[show](#show%20fipspartition) | [delete](#delete%20fipspartition) | [set](#set%20fipspartition) | [add](#add%20fipspartition)

## show fipspartition

Use this operation to get list of FIPS partitions

## Synopsys 

show fipspartition \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the FIPS partitions

## delete fipspartition

Use this operation to delete specified FIPS partition

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete fipspartition id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the FIPS partitions

This is a mandatory parameter.

## set fipspartition

Use this operation to modify FIPS partition

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set fipspartition \[contexts\_size=&lt;long&gt;\] \[key\_store\_size=&lt;long&gt;\] \[crypto\_core\_capacity=&lt;int&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**contexts\_size**

Maximum contexts for the partition

**key\_store\_size**

No of keys for the partition

**crypto\_core\_capacity**

Max Crypto Cores for the partition

## add fipspartition

Use this operation to add SNMP Manager

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add fipspartition partition\_name=&lt;string&gt; contexts\_size=&lt;long&gt; key\_store\_size=&lt;long&gt; crypto\_core\_capacity=&lt;int&gt;

## Parameters {#parameters-3 style="margin-left: 20px;"}

**partition\_name**

FIPS Partition Name

This is a mandatory parameter.

**contexts\_size**

Maximum contexts for the partition

This is a mandatory parameter.

**key\_store\_size**

No of keys for the partition

This is a mandatory parameter.

**crypto\_core\_capacity**

Max Crypto Cores for the partition

This is a mandatory parameter.
