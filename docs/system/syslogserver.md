# syslogserver

Syslog Server

[show](#show%20syslogserver) | [delete](#delete%20syslogserver) | [set](#set%20syslogserver) | [add](#add%20syslogserver)

## show syslogserver

Use this operation to get all the syslog servers

## Synopsys 

show syslogserver \[name=&lt;string&gt;\]

## Parameters 

**name**

Syslog server name

## delete syslogserver

Use this operation to delete a syslog server

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete syslogserver \[name=&lt;string&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**name**

Syslog server name

## set syslogserver

Use this operation to modify a syslog server

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set syslogserver \[log\_level\_all=(false | true)\] \[log\_level\_error=(false | true)\] \[log\_level\_none=(false | true)\] \[log\_level\_warning=(false | true)\] \[port=&lt;int&gt;\] \[log\_level\_critical=(false | true)\] \[log\_level\_info=(false | true)\] \[name=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**log\_level\_all**

Send logs of all levels to this syslog server

**log\_level\_error**

Send logs of level error to this syslog server

**log\_level\_none**

Send no logs to this syslog server

**log\_level\_warning**

Send logs of level warning to this syslog server

**port**

Syslog server port

**log\_level\_critical**

Send logs of level critical to this syslog server

**log\_level\_info**

Send logs of level info to this syslog server

**name**

Syslog server name

## add syslogserver

Use this operation to add a syslog server

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add syslogserver port=&lt;int&gt; ip\_address=&lt;ipaddress&gt; name=&lt;string&gt; \[log\_level\_all=(false | true)\] \[log\_level\_info=(false | true)\] \[log\_level\_none=(false | true)\] \[log\_levels=&lt;string&gt;\] \[log\_level\_warning=(false | true)\] \[log\_level\_critical=(false | true)\] \[log\_level\_error=(false | true)\] \[address\_type=&lt;int&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**port**

Syslog server port

This is a mandatory parameter.

**ip\_address**

Syslog server IP address

This is a mandatory parameter.

**name**

Syslog server name

This is a mandatory parameter.

**log\_level\_all**

Send logs of all levels to this syslog server

**log\_level\_info**

Send logs of level info to this syslog server

**log\_level\_none**

Send no logs to this syslog server

**log\_levels**

Set of all log levels at which messages are sent to this syslog server

**log\_level\_warning**

Send logs of level warning to this syslog server

**log\_level\_critical**

Send logs of level critical to this syslog server

**log\_level\_error**

Send logs of level error to this syslog server

**address\_type**

Configuration Type. Values: 0: IPv4, 1: IPv6
