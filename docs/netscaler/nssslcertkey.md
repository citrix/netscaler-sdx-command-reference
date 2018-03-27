# nssslcertkey

SSL certificate on NetScaler

[show](#show%20nssslcertkey) | [delete](#delete%20nssslcertkey) | [set](#set%20nssslcertkey) | [add](#add%20nssslcertkey) | [do gen\_csr](#do%20nssslcertkey%20gen_csr)

## show nssslcertkey

Use this operation to get certificates on NetScaler Instance(s)

## Synopsys 

show nssslcertkey \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all ssl cert-keys entries. For download operation "id" must be provided in the format &lt;ns\_ip\_address&gt;\_&lt;certkeypair\_name&gt;.tgz

## delete nssslcertkey

Use this operation to delete certificates on NetScaler Instance(s)

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete nssslcertkey id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all ssl cert-keys entries. For download operation "id" must be provided in the format &lt;ns\_ip\_address&gt;\_&lt;certkeypair\_name&gt;.tgz

This is a mandatory parameter.

## set nssslcertkey

Use this operation to modify certificates on NetScaler Instance(s)

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set nssslcertkey id=&lt;string&gt; \[ssl\_certificate=&lt;string&gt;\] \[ssl\_key=&lt;string&gt;\] \[cert\_format=&lt;string&gt;\] \[password=&lt;stringx&gt;\] \[save\_config=(false | true)\] \[no\_domain\_check=(false | true)\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all ssl cert-keys entries. For download operation "id" must be provided in the format &lt;ns\_ip\_address&gt;\_&lt;certkeypair\_name&gt;.tgz

This is a mandatory parameter.

**ssl\_certificate**

Certificate

**ssl\_key**

Key

**cert\_format**

Certificate Format

**password**

The pass-phrase that was used to encrypt the private-key.

**save\_config**

true, if save config is required

**no\_domain\_check**

Specify this option to override the check for matching domain names during certificate update operation

## add nssslcertkey

Use this operation to install certificates on NetScaler Instance(s)

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add nssslcertkey ssl\_certificate=&lt;string&gt; certkeypair\_name=&lt;string&gt; ns\_ip\_address\_arr=&lt;ipaddress...&gt; \[ssl\_key=&lt;string&gt;\] \[cert\_format=&lt;string&gt;\] \[password=&lt;stringx&gt;\] \[save\_config=(false | true)\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**ssl\_certificate**

Certificate

This is a mandatory parameter.

**certkeypair\_name**

Cert Key Pair Name

This is a mandatory parameter.

**ns\_ip\_address\_arr**

List of NetScaler IP Address

This is a mandatory parameter.

**ssl\_key**

Key

**cert\_format**

Certificate Format

**password**

The pass-phrase that was used to encrypt the private-key.

**save\_config**

true, if save config is required

## do nssslcertkey gen\_csr

Use this operation to generate CSR for the certificate

## Synopsys {#synopsys-4 style="margin-left: 20px;"}

do nssslcertkey gen\_csr \[id=&lt;string&gt;\]

## Parameters {#parameters-4 style="margin-left: 20px;"}

**id**

Id is system generated key for all ssl cert-keys entries. For download operation "id" must be provided in the format &lt;ns\_ip\_address&gt;\_&lt;certkeypair\_name&gt;.tgz
