# ntpserver

NTP Server

[show](#show%20ntpserver) | [delete](#delete%20ntpserver) | [set](#set%20ntpserver) | [add](#add%20ntpserver)

## show ntpserver

Use this operation to get NTP Server

## Synopsys 

show ntpserver \[server=&lt;internethost&gt;\]

## Parameters 

**server**

NTP Time Server Address

## delete ntpserver

Use this operation to delete NTP Server

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete ntpserver \[server=&lt;internethost&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**server**

NTP Time Server Address

## set ntpserver

Use this operation to modify NTP Server

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set ntpserver \[minpoll=&lt;int&gt;\] \[preferred\_server=(false | true)\] \[server=&lt;internethost&gt;\] \[autokey=(false | true)\] \[key\_id=&lt;int&gt;\] \[maxpoll=&lt;int&gt;\] \[client=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**minpoll**

Minimum Poll Interval

**preferred\_server**

NTP Server Preferred

**server**

NTP Time Server Address

**autokey**

Autokey Public Key Authentication

**key\_id**

Key Identifier for Symmetric Key Authentication

**maxpoll**

Maximum Poll Interval

**client**

Sender of request, whether from Setup Wizard or direct NTP configuration

## add ntpserver

Use this operation to add NTP Server

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add ntpserver server=&lt;internethost&gt; \[minpoll=&lt;int&gt;\] \[preferred\_server=(false | true)\] \[autokey=(false | true)\] \[key\_id=&lt;int&gt;\] \[maxpoll=&lt;int&gt;\] \[client=&lt;string&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**server**

NTP Time Server Address

This is a mandatory parameter.

**minpoll**

Minimum Poll Interval

**preferred\_server**

NTP Server Preferred

**autokey**

Autokey Public Key Authentication

**key\_id**

Key Identifier for Symmetric Key Authentication

**maxpoll**

Maximum Poll Interval

**client**

Sender of request, whether from Setup Wizard or direct NTP configuration
