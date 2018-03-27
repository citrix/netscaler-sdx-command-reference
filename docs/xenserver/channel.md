# channel

Channels on the system

[show](#show%20channel) | [delete](#delete%20channel) | [set](#set%20channel) | [add](#add%20channel)

## show channel

Use this operation to get channel

## Synopsys 

show channel

## delete channel

Use this operation to delete channels

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete channel channel\_id=&lt;string&gt; \[mtu=&lt;int&gt;\] \[static\_channel\_state=(false | true)\] \[channel\_alias=&lt;string&gt;\] \[state=&lt;string&gt;\] \[channel\_tag\_all\_vlans=(false | true)\] \[channel\_type=&lt;string&gt;\] \[lacp\_channel\_time=&lt;string&gt;\] \[channel\_bandwidth\_high=&lt;int&gt;\] \[channel\_ha\_monitoring=(false | true)\] \[channel\_throughput=&lt;int&gt;\] \[channel\_bandwidth\_normal=&lt;int&gt;\] \[channel\_interface\_list=&lt;string...&gt;\]

## Parameters 

**channel\_id**

Channel ID if this interface represents a channel (LA/1, LA/2 ...)

This is a mandatory parameter.

**mtu**

MTU value, should be between 1500-9126

**static\_channel\_state**

Static channel state (Enabled/Disabled)

**channel\_alias**

Alias name for this channel

**state**

State of the port.

**channel\_tag\_all\_vlans**

If true then all the member interfaces of this channel are tagged. Possible values: true and false

**channel\_type**

Channel type if this interface represents a channel (LACP or Static)

**lacp\_channel\_time**

LACP time. Possible values: SHORT and LONG

**channel\_bandwidth\_high**

Higher end threshold of the channel bandwidth usage in Mbps

**channel\_ha\_monitoring**

HA-monitoring control for the channel. Possible values: true and false

**channel\_throughput**

Minimum required throughput in Mbps for this channel

**channel\_bandwidth\_normal**

Lower end threshold of the channel bandwidth usage in Mbps

**channel\_interface\_list**

Comma separated list of interfaces that are part of this channel if this interface represents a channel (10/1, 10/4)

## set channel

Use this operation to modify channel

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set channel channel\_id=&lt;string&gt; \[mtu=&lt;int&gt;\] \[static\_channel\_state=(false | true)\] \[channel\_alias=&lt;string&gt;\] \[state=&lt;string&gt;\] \[channel\_tag\_all\_vlans=(false | true)\] \[channel\_type=&lt;string&gt;\] \[lacp\_channel\_time=&lt;string&gt;\] \[channel\_bandwidth\_high=&lt;int&gt;\] \[channel\_ha\_monitoring=(false | true)\] \[channel\_throughput=&lt;int&gt;\] \[channel\_bandwidth\_normal=&lt;int&gt;\] \[channel\_interface\_list=&lt;string...&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**channel\_id**

Channel ID if this interface represents a channel (LA/1, LA/2 ...)

This is a mandatory parameter.

**mtu**

MTU value, should be between 1500-9126

**static\_channel\_state**

Static channel state (Enabled/Disabled)

**channel\_alias**

Alias name for this channel

**state**

State of the port.

**channel\_tag\_all\_vlans**

If true then all the member interfaces of this channel are tagged. Possible values: true and false

**channel\_type**

Channel type if this interface represents a channel (LACP or Static)

**lacp\_channel\_time**

LACP time. Possible values: SHORT and LONG

**channel\_bandwidth\_high**

Higher end threshold of the channel bandwidth usage in Mbps

**channel\_ha\_monitoring**

HA-monitoring control for the channel. Possible values: true and false

**channel\_throughput**

Minimum required throughput in Mbps for this channel

**channel\_bandwidth\_normal**

Lower end threshold of the channel bandwidth usage in Mbps

**channel\_interface\_list**

Comma separated list of interfaces that are part of this channel if this interface represents a channel (10/1, 10/4)

## add channel

Use this operation to create channel

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add channel static\_channel\_state=(false | true) channel\_id=&lt;string&gt; channel\_type=&lt;string&gt; channel\_interface\_list=&lt;string...&gt; \[mtu=&lt;int&gt;\] \[channel\_alias=&lt;string&gt;\] \[state=&lt;string&gt;\] \[channel\_tag\_all\_vlans=(false | true)\] \[lacp\_channel\_time=&lt;string&gt;\] \[channel\_bandwidth\_high=&lt;int&gt;\] \[channel\_ha\_monitoring=(false | true)\] \[channel\_throughput=&lt;int&gt;\] \[channel\_bandwidth\_normal=&lt;int&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**static\_channel\_state**

Static channel state (Enabled/Disabled)

This is a mandatory parameter.

**channel\_id**

Channel ID if this interface represents a channel (LA/1, LA/2 ...)

This is a mandatory parameter.

**channel\_type**

Channel type if this interface represents a channel (LACP or Static)

This is a mandatory parameter.

**channel\_interface\_list**

Comma separated list of interfaces that are part of this channel if this interface represents a channel (10/1, 10/4)

This is a mandatory parameter.

**mtu**

MTU value, should be between 1500-9126

**channel\_alias**

Alias name for this channel

**state**

State of the port.

**channel\_tag\_all\_vlans**

If true then all the member interfaces of this channel are tagged. Possible values: true and false

**lacp\_channel\_time**

LACP time. Possible values: SHORT and LONG

**channel\_bandwidth\_high**

Higher end threshold of the channel bandwidth usage in Mbps

**channel\_ha\_monitoring**

HA-monitoring control for the channel. Possible values: true and false

**channel\_throughput**

Minimum required throughput in Mbps for this channel

**channel\_bandwidth\_normal**

Lower end threshold of the channel bandwidth usage in Mbps
