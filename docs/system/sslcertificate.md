# sslcertificate

Install SSL certificate on Management Service

[show](#show%20sslcertificate) | [add](#add%20sslcertificate)

## show sslcertificate

Use this operation to get certificate on Management Service

## Synopsys 

show sslcertificate

## add sslcertificate

Use this operation to install certificate on Management Service

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

add sslcertificate ssl\_certificate=&lt;string&gt; \[status=&lt;string&gt;\] \[subject=&lt;string&gt;\] \[ssl\_key=&lt;string&gt;\] \[valid\_from=&lt;string&gt;\] \[days\_to\_expiry=&lt;int&gt;\] \[public\_key\_size=&lt;int&gt;\] \[public\_key\_algorithm=&lt;string&gt;\] \[password=&lt;stringx&gt;\] \[version=&lt;string&gt;\] \[serial\_number=&lt;string&gt;\] \[signature\_algorithm=&lt;string&gt;\] \[issuer=&lt;string&gt;\] \[valid\_to=&lt;string&gt;\] \[fingerprint=&lt;string&gt;\]

## Parameters 

**ssl\_certificate**

Certificate

This is a mandatory parameter.

**status**

Tells whether the certificate is still valid or not

**subject**

Subject

**ssl\_key**

Key

**valid\_from**

Valid From

**days\_to\_expiry**

Days before SSL certificate expires

**public\_key\_size**

Public Key Size

**public\_key\_algorithm**

Public Key Algorithm

**password**

The pass-phrase that was used to encrypt the private-key.

**version**

Version

**serial\_number**

Serial Number

**signature\_algorithm**

Signature Algorithm

**issuer**

Issuer

**valid\_to**

Valid To

**fingerprint**

SHA-1 Fingerprint of MAS SSL Certificate
