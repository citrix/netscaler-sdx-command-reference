# raidLogicalDrive

Raid Logical Drive

[show](#show%20raidLogicalDrive) | [delete](#delete%20raidLogicalDrive) | [add](#add%20raidLogicalDrive)

## show raidLogicalDrive

Use this operation to get logical disks

## Synopsys 

show raidLogicalDrive \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all logical drives

## delete raidLogicalDrive

Use this operation to delete logical disk

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete raidLogicalDrive \[id=&lt;string&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all logical drives

## add raidLogicalDrive

Use this operation to create logical disk

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

add raidLogicalDrive \[name=&lt;string&gt;\] \[adapter\_id=&lt;int&gt;\] \[state=&lt;string&gt;\] \[sr\_uuid=&lt;string&gt;\] \[drives=&lt;string&gt;\] \[targetid=&lt;int&gt;\] \[virtualdrive=&lt;int&gt;\] \[size=&lt;string&gt;\] \[force\_clean=(false | true)\] \[physical\_disk\_slot\_1=&lt;string&gt;\] \[physical\_disk\_slot\_2=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**name**

Logical Drive Name

**adapter\_id**

Adapter ID

**state**

State

**sr\_uuid**

SR UUID

**drives**

Drives

**targetid**

Target ID

**virtualdrive**

Virtual Drive

**size**

Logical Drive Size

**force\_clean**

Force Clean Physical Disks before creating logical drive

**physical\_disk\_slot\_1**

First Slot for Raid Logical Drive

**physical\_disk\_slot\_2**

Second Slot for Raid Logical Drive
