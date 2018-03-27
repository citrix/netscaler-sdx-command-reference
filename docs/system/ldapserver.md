# ldapserver

LDAP Server

[show](#show%20ldapserver) | [delete](#delete%20ldapserver) | [set](#set%20ldapserver) | [add](#add%20ldapserver)

## show ldapserver

Use this operation to get LDAP server details

## Synopsys 

show ldapserver \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the ldap servers

## delete ldapserver

Use this operation to delete LDAP server

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete ldapserver id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the ldap servers

This is a mandatory parameter.

## set ldapserver

Use this operation to modify LDAP server

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set ldapserver id=&lt;string&gt; name=&lt;string&gt; ip\_address=&lt;internethost&gt; \[port=&lt;int&gt;\] \[validate\_ldap\_server\_certs=(false | true)\] \[ldap\_host\_name=&lt;string&gt;\] \[sec\_type=&lt;string&gt;\] \[type=&lt;string&gt;\] \[subattribute\_name=&lt;string&gt;\] \[change\_password=(false | true)\] \[follow\_referrals=(false | true)\] \[max\_nesting\_level=&lt;int&gt;\] \[group\_search\_filter=&lt;string&gt;\] \[group\_attr\_name=&lt;string&gt;\] \[max\_ldap\_referrals=&lt;int&gt;\] \[group\_search\_attribute=&lt;string&gt;\] \[group\_search\_subattribute=&lt;string&gt;\] \[auth\_timeout=&lt;int&gt;\] \[nested\_group\_extraction=(false | true)\] \[group\_name\_identifier=&lt;string&gt;\] \[default\_authentication\_group=&lt;string&gt;\] \[bind\_passwd=&lt;stringx&gt;\] \[bind\_dn=&lt;string&gt;\] \[search\_filter=&lt;string&gt;\] \[login\_name=&lt;string&gt;\] \[base\_dn=&lt;string&gt;\] \[address\_type=&lt;int&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the ldap servers

This is a mandatory parameter.

**name**

Name of LDAP server

This is a mandatory parameter.

**ip\_address**

The IP address of the LDAP server.

This is a mandatory parameter.

**port**

The port number on which the LDAP server is running

**validate\_ldap\_server\_certs**

Validate LDAP Server Certificate

**ldap\_host\_name**

Host Name on the certificate from LDAP Server

**sec\_type**

The communication type between the system and the LDAP server

**type**

The type of LDAP server

**subattribute\_name**

The Sub-Attribute name for group extraction from LDAP server

**change\_password**

Enable change of the user

**follow\_referrals**

Enable following LDAP referrals received from LDAP server

**max\_nesting\_level**

Number of levels at which group extraction is allowed

**group\_search\_filter**

String to be combined with the default LDAP group search string to form the search value

**group\_attr\_name**

The Attribute name for group extraction from the LDAP server

**max\_ldap\_referrals**

Maximum number of ldap referrals to follow

**group\_search\_attribute**

LDAP group search attribute. Used to determine to which groups a group belongs

**group\_search\_subattribute**

LDAP group search subattribute. Used to determine to which groups a group belongs.

**auth\_timeout**

The maximum number of seconds the system will wait for a response from the LDAP server

**nested\_group\_extraction**

Enable Nested Group Extraction

**group\_name\_identifier**

Name that uniquely identifies a group in LDAP server

**default\_authentication\_group**

This is the default group

**bind\_passwd**

The password used to bind to the LDAP server

**bind\_dn**

The full distinguished name used to bind to the LDAP server

**search\_filter**

The String to be combined with the default LDAP user search string to form the value

**login\_name**

The name attribute used by the system to query the external LDAP server

**base\_dn**

The base or node where the ldapsearch should start

**address\_type**

Configuration Type. Values: 0: IPv4, 1: IPv6, -1: Hostname

## add ldapserver

Use this operation to add LDAP server

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add ldapserver type=&lt;string&gt; name=&lt;string&gt; ip\_address=&lt;internethost&gt; \[port=&lt;int&gt;\] \[validate\_ldap\_server\_certs=(false | true)\] \[ldap\_host\_name=&lt;string&gt;\] \[sec\_type=&lt;string&gt;\] \[subattribute\_name=&lt;string&gt;\] \[change\_password=(false | true)\] \[follow\_referrals=(false | true)\] \[max\_nesting\_level=&lt;int&gt;\] \[group\_search\_filter=&lt;string&gt;\] \[group\_attr\_name=&lt;string&gt;\] \[max\_ldap\_referrals=&lt;int&gt;\] \[group\_search\_attribute=&lt;string&gt;\] \[group\_search\_subattribute=&lt;string&gt;\] \[auth\_timeout=&lt;int&gt;\] \[nested\_group\_extraction=(false | true)\] \[group\_name\_identifier=&lt;string&gt;\] \[default\_authentication\_group=&lt;string&gt;\] \[bind\_passwd=&lt;stringx&gt;\] \[bind\_dn=&lt;string&gt;\] \[search\_filter=&lt;string&gt;\] \[login\_name=&lt;string&gt;\] \[base\_dn=&lt;string&gt;\] \[address\_type=&lt;int&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**type**

The type of LDAP server

This is a mandatory parameter.

**name**

Name of LDAP server

This is a mandatory parameter.

**ip\_address**

The IP address of the LDAP server.

This is a mandatory parameter.

**port**

The port number on which the LDAP server is running

**validate\_ldap\_server\_certs**

Validate LDAP Server Certificate

**ldap\_host\_name**

Host Name on the certificate from LDAP Server

**sec\_type**

The communication type between the system and the LDAP server

**subattribute\_name**

The Sub-Attribute name for group extraction from LDAP server

**change\_password**

Enable change of the user

**follow\_referrals**

Enable following LDAP referrals received from LDAP server

**max\_nesting\_level**

Number of levels at which group extraction is allowed

**group\_search\_filter**

String to be combined with the default LDAP group search string to form the search value

**group\_attr\_name**

The Attribute name for group extraction from the LDAP server

**max\_ldap\_referrals**

Maximum number of ldap referrals to follow

**group\_search\_attribute**

LDAP group search attribute. Used to determine to which groups a group belongs

**group\_search\_subattribute**

LDAP group search subattribute. Used to determine to which groups a group belongs.

**auth\_timeout**

The maximum number of seconds the system will wait for a response from the LDAP server

**nested\_group\_extraction**

Enable Nested Group Extraction

**group\_name\_identifier**

Name that uniquely identifies a group in LDAP server

**default\_authentication\_group**

This is the default group

**bind\_passwd**

The password used to bind to the LDAP server

**bind\_dn**

The full distinguished name used to bind to the LDAP server

**search\_filter**

The String to be combined with the default LDAP user search string to form the value

**login\_name**

The name attribute used by the system to query the external LDAP server

**base\_dn**

The base or node where the ldapsearch should start

**address\_type**

Configuration Type. Values: 0: IPv4, 1: IPv6, -1: Hostname
