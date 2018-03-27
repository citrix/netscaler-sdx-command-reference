# backupexternalstorage

Backup File External storage

[show](#show%20backupexternalstorage) | [set](#set%20backupexternalstorage)

## show backupexternalstorage

Use this operation to display external transfer server information

## Synopsys 

show backupexternalstorage \[server=&lt;internethost&gt;\]

## Parameters 

**server**

External server IP Address/Hostname

## set backupexternalstorage

Use this operation to modify the external transfer server information

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

set backupexternalstorage \[port=&lt;int&gt;\] \[username=&lt;string&gt;\] \[transfer\_protocol=&lt;string&gt;\] \[directory\_path=&lt;string&gt;\] \[parent\_name=&lt;string&gt;\] \[delete\_from\_svm=(false | true)\] \[server=&lt;internethost&gt;\] \[password=&lt;stringx&gt;\] \[parent\_id=&lt;string&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**port**

External transfer server port

**username**

Uername

**transfer\_protocol**

File transfer Protocol: SCP, SFTP or FTP

**directory\_path**

External server directory path where backup file will be uploaded

**parent\_name**

**delete\_from\_svm**

Password for backup file encryption

**server**

External server IP Address/Hostname

**password**

Password

**parent\_id**