# networkconfig

SDX Network Configuration

[show](#show%20networkconfig) | [set](#set%20networkconfig)

## show networkconfig

Use this operation to get SDX network configuration

## Synopsys 

show networkconfig

## set networkconfig

Use this operation to modify SDX network configuration

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

set networkconfig gateway=&lt;ipaddress&gt; config\_type=&lt;int&gt; xen\_ip\_address=&lt;ipaddress&gt; network\_interface=&lt;string&gt; netmask=&lt;ipaddress&gt; \[gateway\_ipv6=&lt;ipaddress6&gt;\] \[dns=&lt;ipaddress4&gt;\] \[svm\_ip\_address=&lt;ipaddress&gt;\] \[host\_ip\_address=&lt;ipaddress&gt;\] \[apply\_svm\_ip=(false | true)\] \[svm\_ipv6\_address=&lt;ipaddress6net&gt;\] \[dns\_v6=&lt;ipaddress6&gt;\] \[additional\_dns1=&lt;ipaddress&gt;\] \[additional\_dns2=&lt;ipaddress&gt;\] \[skip\_reboot=(false | true)\] \[init\_status=&lt;int&gt;\] \[act\_id=&lt;string&gt;\] \[sync\_to\_vm=(false | true)\]

## Parameters 

**gateway**

Gateway

This is a mandatory parameter.

**config\_type**

Configuration Type. Values: 0: IPv4, 1: IPv6, 2: Both

This is a mandatory parameter.

**xen\_ip\_address**

XenServer IP Address

This is a mandatory parameter.

**network\_interface**

Interface on which management needs to be enabled

This is a mandatory parameter.

**netmask**

Netmask

This is a mandatory parameter.

**gateway\_ipv6**

Gateway IPv6 Address

**dns**

DNS Server

**svm\_ip\_address**

Management Service IP Address

**host\_ip\_address**

Host IP Address

**apply\_svm\_ip**

Apply SVM IP

**svm\_ipv6\_address**

Management Service IPv6 Address

**dns\_v6**

DNS Server IPv6 Address

**additional\_dns1**

Additional DNS Server. Can be IPv4 or IPv6

**additional\_dns2**

Additional DNS Server. Can be IPv4 or IPv6

**skip\_reboot**

Set CB reboot required option during PUT

**init\_status**

System initialize status

**act\_id**

Activity Id

**sync\_to\_vm**

Set option to sync or not to sync with CB
