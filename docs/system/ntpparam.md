# ntpparam

NTP Parameters

[show](#show%20ntpparam) | [set](#set%20ntpparam)

## show ntpparam

Use this operation to get NTP Server

## Synopsys 

show ntpparam

## set ntpparam

Use this operation to modify NTP Server

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

set ntpparam \[trusted\_key\_list=&lt;int...&gt;\] \[automax\_logsec=&lt;int&gt;\] \[authentication=(false | true)\] \[revoke\_logsec=&lt;int&gt;\]

## Parameters 

**trusted\_key\_list**

List of Trusted Key Identifiers for Symmetric Key Cryptography

**automax\_logsec**

Automax Interval (as power of 2 in seconds)

**authentication**

Authentication Enabled

**revoke\_logsec**

Revoke Interval (as power of 2 in seconds)
