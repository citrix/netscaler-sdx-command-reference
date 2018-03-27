# hostinterface

XenServer Interface

[show](#show%20hostinterface) | [set](#set%20hostinterface) | [do custom](#do%20hostinterface%20custom)

## show hostinterface

Use this operation to get interface/channel

## Synopsys 

show hostinterface \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key

## set hostinterface

Use this operation to modify interface/channel

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

set hostinterface mapped\_port=&lt;string&gt; \[mtu=&lt;int&gt;\] \[port=&lt;string&gt;\] \[apply\_mac\_address=(false | true)\] \[range=&lt;string&gt;\] \[base\_mac\_address=&lt;string&gt;\] \[add\_mac\_address=(false | true)\] \[interface\_type=&lt;string&gt;\] \[flow\_control\_tx=(false | true)\] \[adv\_auto\_neg=(false | true)\] \[speed=&lt;string&gt;\] \[cpu\_socket=&lt;string&gt;\] \[flow\_control\_rx=(false | true)\] \[state=&lt;string&gt;\] \[flow\_control\_auto\_neg=(false | true)\] \[act\_id=&lt;string&gt;\] \[device\_name=&lt;string&gt;\] \[port\_type=&lt;string&gt;\] \[duplex=&lt;string&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**mapped\_port**

Mapped Port Name Ex: eth0

This is a mandatory parameter.

**mtu**

MTU value, should be between 1500-9126

**port**

Port Name Ex: 10/1

**apply\_mac\_address**

Apply Mac Address

**range**

Range for Base Mac Address

**base\_mac\_address**

Mac Address

**add\_mac\_address**

Add Mac Address

**interface\_type**

Indicates if this is an interface or a channel or a member interface of a channel

**flow\_control\_tx**

TX Pause

**adv\_auto\_neg**

true if the advertised auto-negotiation for the port is true

**speed**

Actual speed

**cpu\_socket**

CPU Socket to which this interface belong to

**flow\_control\_rx**

RX Pause

**state**

State of the port.

**flow\_control\_auto\_neg**

Auto Negotiation For Flow Control

**act\_id**

Activity Id

**device\_name**

Device Name

**port\_type**

Port Type

**duplex**

Duplex

## do hostinterface custom

Use this operation to reset interface settings

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

do hostinterface custom \[id=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key
