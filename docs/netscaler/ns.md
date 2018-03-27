# ns

NetScaler

[do stop](#do%20ns%20stop) | [show](#show%20ns) | [do start](#do%20ns%20start) | [do reboot](#do%20ns%20reboot) | [delete](#delete%20ns) | [set](#set%20ns) | [do force\_reboot](#do%20ns%20force_reboot) | [add](#add%20ns) | [do force\_stop](#do%20ns%20force_stop)

## do ns stop

Use this operation to stop NetScaler Instance

## Synopsys 

do ns stop \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the NetScaler Instances

## show ns

Use this operation to get NetScaler Instance

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

show ns \[id=&lt;string&gt;\] \[name=&lt;string&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the NetScaler Instances

**name**

Name of managed device

## do ns start

Use this operation to start NetScaler Instance

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

do ns start \[id=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the NetScaler Instances

## do ns reboot

Use this operation to reboot NetScaler Instance

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

do ns reboot \[id=&lt;string&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**id**

Id is system generated key for all the NetScaler Instances

## delete ns

Use this operation to delete NetScaler Instances

## Synopsys {#synopsys-4 style="margin-left: 20px;"}

delete ns id=&lt;string&gt;

## Parameters {#parameters-4 style="margin-left: 20px;"}

**id**

Id is system generated key for all the NetScaler Instances

This is a mandatory parameter.

## set ns

Use this operation to modify NetScaler Instance

## Synopsys {#synopsys-5 style="margin-left: 20px;"}

set ns id=&lt;string&gt; \[name=&lt;string&gt;\] \[ip\_address=&lt;ipaddress&gt;\] \[netmask=&lt;ipaddress&gt;\] \[gateway=&lt;ipaddress&gt;\] \[license=&lt;string&gt;\] \[admin\_profile\_name=&lt;string&gt;\] \[description=&lt;string&gt;\] \[vm\_memory\_total=&lt;doublelong&gt;\] \[num\_of\_ssl\_chips=&lt;int&gt;\] \[throughput=&lt;doublelong&gt;\] \[pps=&lt;doublelong&gt;\] \[number\_of\_cores=&lt;int&gt;\] \[reboot\_vm\_on\_cpu\_change=(false | true)\] \[password=&lt;stringx&gt;\] \[cmd\_policy=&lt;string&gt;\] \[l2\_enabled=(false | true)\] \[if\_0\_1=(false | true)\] \[if\_0\_2=(false | true)\] \[la\_mgmt=(false | true)\] \[vlan\_id\_0\_1=&lt;int&gt;\] \[vlan\_id\_0\_2=&lt;int&gt;\] \[network\_interfaces=&lt;network\_interface...&gt;\] \[nsvlan\_id=&lt;int&gt;\] \[vlan\_type=&lt;int&gt;\] \[nsvlan\_tagged=(false | true)\] \[nsvlan\_interfaces=&lt;string...&gt;\]

## Parameters {#parameters-5 style="margin-left: 20px;"}

**id**

Id is system generated key for all the NetScaler Instances

This is a mandatory parameter.

**name**

Name of managed device

**ip\_address**

IP Address for this managed device

**netmask**

Netmask of managed device

**gateway**

Default Gateway of managed device

**license**

Feature License for NetScaler Instance, needs to be set while provisioning (standard, enterprise, platinum, SWG)

**admin\_profile\_name**

Device Profile Name that is attached with this managed device

**description**

Description of managed device

**vm\_memory\_total**

Total Memory of VM Instance in MB

**num\_of\_ssl\_chips**

Assign number of ssl virtual functions to VM Instance

**throughput**

Assign throughput in Mbps to VM Instance

**pps**

Assign packets per seconds to NetScaler Instance

**number\_of\_cores**

Number of cores that are assigned to VM Instance

**reboot\_vm\_on\_cpu\_change**

Reboot VMs on CPU change during resource allocation

**password**

Password for specified user on NetScaler Instance

**cmd\_policy**

true if you want to allow shell/sftp/scp access to NetScaler Instance administrator

**l2\_enabled**

L2mode status of VM Instance

**if\_0\_1**

Network 0/1 on VM Instance

**if\_0\_2**

Network 0/2 on VM Instance

**la\_mgmt**

Bond consisting of management ports on VM Instance

**vlan\_id\_0\_1**

VLAN id for the management interface 0/1

**vlan\_id\_0\_2**

VLAN id for the management interface 0/2

**network\_interfaces**

Network Interfaces

**nsvlan\_id**

VLAN Id

**vlan\_type**

VLAN Type, NS or L2 VLAN

**nsvlan\_tagged**

NSVLAN Tagged

**nsvlan\_interfaces**

VLAN Interfaces

## do ns force\_reboot

Use this operation to force reboot NetScaler Instance

## Synopsys {#synopsys-6 style="margin-left: 20px;"}

do ns force\_reboot \[id=&lt;string&gt;\]

## Parameters {#parameters-6 style="margin-left: 20px;"}

**id**

Id is system generated key for all the NetScaler Instances

## add ns

Use this operation to add NetScaler Instance

## Synopsys {#synopsys-7 style="margin-left: 20px;"}

add ns ip\_address=&lt;ipaddress&gt; \[gateway=&lt;ipaddress&gt;\] \[l2\_enabled=(false | true)\] \[nsvlan\_interfaces=&lt;string...&gt;\] \[pps=&lt;doublelong&gt;\] \[throughput=&lt;doublelong&gt;\] \[la\_mgmt=(false | true)\] \[nsvlan\_tagged=(false | true)\] \[license=&lt;string&gt;\] \[username=&lt;string&gt;\] \[cmd\_policy=&lt;string&gt;\] \[name=&lt;string&gt;\] \[number\_of\_cores=&lt;int&gt;\] \[vlan\_id\_0\_1=&lt;int&gt;\] \[if\_0\_1=(false | true)\] \[netmask=&lt;ipaddress&gt;\] \[vlan\_id\_0\_2=&lt;int&gt;\] \[description=&lt;string&gt;\] \[if\_0\_2=(false | true)\] \[network\_interfaces=&lt;network\_interface...&gt;\] \[reboot\_vm\_on\_cpu\_change=(false | true)\] \[vlan\_type=&lt;int&gt;\] \[xva\_file\_name=&lt;string&gt;\] \[password=&lt;stringx&gt;\] \[vm\_memory\_total=&lt;doublelong&gt;\] \[nsvlan\_id=&lt;int&gt;\]

## Parameters {#parameters-7 style="margin-left: 20px;"}

**ip\_address**

IP Address for this managed device

This is a mandatory parameter.

**gateway**

Default Gateway of managed device

**l2\_enabled**

L2mode status of VM Instance

**nsvlan\_interfaces**

VLAN Interfaces

**pps**

Assign packets per seconds to NetScaler Instance

**throughput**

Assign throughput in Mbps to VM Instance

**la\_mgmt**

Bond consisting of management ports on VM Instance

**nsvlan\_tagged**

NSVLAN Tagged

**license**

Feature License for NetScaler Instance, needs to be set while provisioning (standard, enterprise, platinum, SWG)

**username**

User Name (except nsroot) to be configured on NetScaler Instance

**cmd\_policy**

true if you want to allow shell/sftp/scp access to NetScaler Instance administrator

**name**

Name of managed device

**number\_of\_cores**

Number of cores that are assigned to VM Instance

**vlan\_id\_0\_1**

VLAN id for the management interface 0/1

**if\_0\_1**

Network 0/1 on VM Instance

**netmask**

Netmask of managed device

**vlan\_id\_0\_2**

VLAN id for the management interface 0/2

**description**

Description of managed device

**if\_0\_2**

Network 0/2 on VM Instance

**network\_interfaces**

Network Interfaces

**reboot\_vm\_on\_cpu\_change**

Reboot VMs on CPU change during resource allocation

**vlan\_type**

VLAN Type, NS or L2 VLAN

**xva\_file\_name**

Image Name, This parameter is used while provisioning VM Instance with XVA image, template\_name is given priority if provided along with image\_name

**password**

Password for specified user on NetScaler Instance

**vm\_memory\_total**

Total Memory of VM Instance in MB

**nsvlan\_id**

VLAN Id

## do ns force\_stop

Use this operation to force stop NetScaler Instance

## Synopsys {#synopsys-8 style="margin-left: 20px;"}

do ns force\_stop \[id=&lt;string&gt;\]

## Parameters {#parameters-8 style="margin-left: 20px;"}

**id**

Id is system generated key for all the NetScaler Instances
