# radiusserver

Radius Server configuration

[show](#show%20radiusserver) | [delete](#delete%20radiusserver) | [set](#set%20radiusserver) | [add](#add%20radiusserver)

## show radiusserver

Use this operation to get Radius server details

## Synopsys 

show radiusserver \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the radius servers

## delete radiusserver

Use this operation to delete Radius server

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete radiusserver id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the radius servers

This is a mandatory parameter.

## set radiusserver

Use this operation to modify Radius server

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set radiusserver id=&lt;string&gt; ip\_address=&lt;internethost&gt; name=&lt;string&gt; \[port=&lt;int&gt;\] \[ip\_vendor\_id=&lt;int&gt;\] \[ip\_attribute\_type=&lt;int&gt;\] \[nas\_id=&lt;string&gt;\] \[auth\_timeout=&lt;int&gt;\] \[pwd\_attribute\_type=&lt;int&gt;\] \[accounting=(false | true)\] \[group\_vendor\_id=&lt;int&gt;\] \[group\_attribute\_type=&lt;int&gt;\] \[pwd\_vendor\_id=&lt;int&gt;\] \[default\_authentication\_group=&lt;string&gt;\] \[group\_separator=&lt;string&gt;\] \[pass\_encoding=&lt;string&gt;\] \[radius\_key=&lt;stringx&gt;\] \[enable\_nas\_ip=(false | true)\] \[groups\_prefix=&lt;string&gt;\] \[address\_type=&lt;int&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the radius servers

This is a mandatory parameter.

**ip\_address**

IP Address of radius server

This is a mandatory parameter.

**name**

Name of radius server

This is a mandatory parameter.

**port**

Port number of radius server

**ip\_vendor\_id**

The vendor ID of the attribute in the RADIUS response which denotes the intranet IP

**ip\_attribute\_type**

The attribute type of the remote IP address attribute in a RADIUS response

**nas\_id**

NAS ID

**auth\_timeout**

The maximum number of seconds the system will wait for a response from the Radius server

**pwd\_attribute\_type**

The attribute type of the password attribute in a RADIUS response.

**accounting**

Enable accounting in the radius server

**group\_vendor\_id**

Vendor ID for RADIUS group extraction

**group\_attribute\_type**

Attribute type for RADIUS group extraction

**pwd\_vendor\_id**

Vendor ID of the password in the RADIUS response. Used to extract the user password

**default\_authentication\_group**

This is the default group that is chosen when the authentication succeeds in addition to extracted groups

**group\_separator**

Group separator string that delimits group names within a RADIUS attribute for RADIUS group extraction

**pass\_encoding**

Enable password encoding in RADIUS packets send to the RADIUS server

**radius\_key**

Key of radius server

**enable\_nas\_ip**

Enable NAS IP extraction

**groups\_prefix**

Prefix string that precedes group names within a RADIUS attribute for RADIUS group extraction

**address\_type**

Configuration Type. Values: 0: IPv4, 1: IPv6, -1: Hostname

## add radiusserver

Use this operation to add Radius server

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add radiusserver ip\_address=&lt;internethost&gt; name=&lt;string&gt; radius\_key=&lt;stringx&gt; \[port=&lt;int&gt;\] \[ip\_vendor\_id=&lt;int&gt;\] \[ip\_attribute\_type=&lt;int&gt;\] \[nas\_id=&lt;string&gt;\] \[auth\_timeout=&lt;int&gt;\] \[pwd\_attribute\_type=&lt;int&gt;\] \[accounting=(false | true)\] \[group\_vendor\_id=&lt;int&gt;\] \[group\_attribute\_type=&lt;int&gt;\] \[pwd\_vendor\_id=&lt;int&gt;\] \[default\_authentication\_group=&lt;string&gt;\] \[group\_separator=&lt;string&gt;\] \[pass\_encoding=&lt;string&gt;\] \[enable\_nas\_ip=(false | true)\] \[groups\_prefix=&lt;string&gt;\] \[address\_type=&lt;int&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**ip\_address**

IP Address of radius server

This is a mandatory parameter.

**name**

Name of radius server

This is a mandatory parameter.

**radius\_key**

Key of radius server

This is a mandatory parameter.

**port**

Port number of radius server

**ip\_vendor\_id**

The vendor ID of the attribute in the RADIUS response which denotes the intranet IP

**ip\_attribute\_type**

The attribute type of the remote IP address attribute in a RADIUS response

**nas\_id**

NAS ID

**auth\_timeout**

The maximum number of seconds the system will wait for a response from the Radius server

**pwd\_attribute\_type**

The attribute type of the password attribute in a RADIUS response.

**accounting**

Enable accounting in the radius server

**group\_vendor\_id**

Vendor ID for RADIUS group extraction

**group\_attribute\_type**

Attribute type for RADIUS group extraction

**pwd\_vendor\_id**

Vendor ID of the password in the RADIUS response. Used to extract the user password

**default\_authentication\_group**

This is the default group that is chosen when the authentication succeeds in addition to extracted groups

**group\_separator**

Group separator string that delimits group names within a RADIUS attribute for RADIUS group extraction

**pass\_encoding**

Enable password encoding in RADIUS packets send to the RADIUS server

**enable\_nas\_ip**

Enable NAS IP extraction

**groups\_prefix**

Prefix string that precedes group names within a RADIUS attribute for RADIUS group extraction

**address\_type**

Configuration Type. Values: 0: IPv4, 1: IPv6, -1: Hostname
