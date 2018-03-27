# smsserver

SMS server properties

[show](#show%20smsserver) | [delete](#delete%20smsserver) | [set](#set%20smsserver) | [add](#add%20smsserver)

## show smsserver

Use this operation to get sms server details.

## Synopsys 

show smsserver \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the sms server

## delete smsserver

Use this operation to delete sms server

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete smsserver id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the sms server

This is a mandatory parameter.

## set smsserver

Use this operation to modify sms server

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set smsserver id=&lt;string&gt; \[is\_ssl=(false | true)\] \[optional2\_key=&lt;string&gt;\] \[to\_separator=&lt;string&gt;\] \[to\_key=&lt;string&gt;\] \[username\_key=&lt;string&gt;\] \[message\_word\_separator=&lt;string&gt;\] \[optional\_key=&lt;string&gt;\] \[type=&lt;string&gt;\] \[base\_url=&lt;string&gt;\] \[message\_key=&lt;string&gt;\] \[optional\_val=&lt;string&gt;\] \[server\_name=&lt;string&gt;\] \[optional2\_val1=&lt;string&gt;\] \[password\_val=&lt;stringx&gt;\] \[username\_val=&lt;string&gt;\] \[password\_key=&lt;string&gt;\] \[optional3\_key=&lt;string&gt;\] \[optional3\_val=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the sms server

This is a mandatory parameter.

**is\_ssl**

Is SSL support configured.

**optional2\_key**

Optional2 key for the sms server

**to\_separator**

To list seperater for the sms server

**to\_key**

To key for the sms server

**username\_key**

Username key for the sms server

**message\_word\_separator**

Message Word Seperater for the sms server

**optional\_key**

Optional1 key for the sms server

**type**

HTTP type supported for the sms server

**base\_url**

Base URL for the sms server, without payload

**message\_key**

Message key for the sms server

**optional\_val**

Optional1 Val for the sms server

**server\_name**

SMS server name

**optional2\_val1**

Optional2 Val for the sms server

**password\_val**

Password Val for the sms server

**username\_val**

Username val for the sms server

**password\_key**

Password key for the sms server

**optional3\_key**

Optional3 key for the sms server

**optional3\_val**

Optional3 Val for the sms server

## add smsserver

Use this operation to add sms server

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add smsserver to\_key=&lt;string&gt; username\_key=&lt;string&gt; type=&lt;string&gt; base\_url=&lt;string&gt; message\_key=&lt;string&gt; server\_name=&lt;string&gt; password\_val=&lt;stringx&gt; username\_val=&lt;string&gt; password\_key=&lt;string&gt; \[is\_ssl=(false | true)\] \[optional2\_key=&lt;string&gt;\] \[to\_separator=&lt;string&gt;\] \[message\_word\_separator=&lt;string&gt;\] \[optional\_key=&lt;string&gt;\] \[optional\_val=&lt;string&gt;\] \[optional2\_val1=&lt;string&gt;\] \[optional3\_key=&lt;string&gt;\] \[optional3\_val=&lt;string&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**to\_key**

To key for the sms server

This is a mandatory parameter.

**username\_key**

Username key for the sms server

This is a mandatory parameter.

**type**

HTTP type supported for the sms server

This is a mandatory parameter.

**base\_url**

Base URL for the sms server, without payload

This is a mandatory parameter.

**message\_key**

Message key for the sms server

This is a mandatory parameter.

**server\_name**

SMS server name

This is a mandatory parameter.

**password\_val**

Password Val for the sms server

This is a mandatory parameter.

**username\_val**

Username val for the sms server

This is a mandatory parameter.

**password\_key**

Password key for the sms server

This is a mandatory parameter.

**is\_ssl**

Is SSL support configured.

**optional2\_key**

Optional2 key for the sms server

**to\_separator**

To list seperater for the sms server

**message\_word\_separator**

Message Word Seperater for the sms server

**optional\_key**

Optional1 key for the sms server

**optional\_val**

Optional1 Val for the sms server

**optional2\_val1**

Optional2 Val for the sms server

**optional3\_key**

Optional3 key for the sms server

**optional3\_val**

Optional3 Val for the sms server
