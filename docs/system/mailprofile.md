# mailprofile

Mail profile

[show](#show%20mailprofile) | [delete](#delete%20mailprofile) | [set](#set%20mailprofile) | [add](#add%20mailprofile)

## show mailprofile

Use this operation to get mail profile.

## Synopsys 

show mailprofile \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the mail profile.

## delete mailprofile

Use this operation to delete mail profile.

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete mailprofile id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the mail profile.

This is a mandatory parameter.

## set mailprofile

Use this operation to modify mail profile.

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set mailprofile id=&lt;string&gt; \[to\_list=&lt;string&gt;\] \[server\_name=&lt;internethost&gt;\] \[cc\_list=&lt;string&gt;\] \[profile\_name=&lt;string&gt;\] \[bcc\_list=&lt;string&gt;\] \[sender\_mail\_address=&lt;string&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the mail profile.

This is a mandatory parameter.

**to\_list**

List of to whom send the mail.

**server\_name**

SMTP server name

**cc\_list**

List to whom CC the mail.

**profile\_name**

Profile name for the mail setting.

**bcc\_list**

List to whom BCC the mail.

**sender\_mail\_address**

Email Address from where mail is send

## add mailprofile

Use this operation to add mail profile.

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add mailprofile to\_list=&lt;string&gt; server\_name=&lt;internethost&gt; profile\_name=&lt;string&gt; \[cc\_list=&lt;string&gt;\] \[bcc\_list=&lt;string&gt;\] \[sender\_mail\_address=&lt;string&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**to\_list**

List of to whom send the mail.

This is a mandatory parameter.

**server\_name**

SMTP server name

This is a mandatory parameter.

**profile\_name**

Profile name for the mail setting.

This is a mandatory parameter.

**cc\_list**

List to whom CC the mail.

**bcc\_list**

List to whom BCC the mail.

**sender\_mail\_address**

Email Address from where mail is send
