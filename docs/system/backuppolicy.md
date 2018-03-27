# backuppolicy

Backup Policy

[show](#show%20backuppolicy) | [set](#set%20backuppolicy)

## show backuppolicy

Use this operation to get backup policy to view the number of previous backups to retain and backup file encryption details

## Synopsys 

show backuppolicy \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key

## set backuppolicy

Use this operation to modify the number of previous backups to retain and backup file encryption details

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

set backuppolicy backup\_to\_retain=&lt;int&gt; \[encrypt\_backup\_file=(false | true)\] \[policy\_name=&lt;string&gt;\] \[external\_storage\_info=&lt;backup\_external\_storage&gt;\] \[enable\_external\_transfer=(false | true)\] \[backup\_password=&lt;stringx&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**backup\_to\_retain**

Number of previous backups to retain

This is a mandatory parameter.

**encrypt\_backup\_file**

Encrypts backup files

**policy\_name**

Policy Name

**external\_storage\_info**

Information of the External storage for backup file

**enable\_external\_transfer**

Enable transfer of backup file to external server

**backup\_password**

Password for backup file encryption
