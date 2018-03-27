# systemuser

System User

[show](#show%20systemuser) | [delete](#delete%20systemuser) | [set](#set%20systemuser) | [add](#add%20systemuser)

## show systemuser

Use this operation to get system users

## Synopsys 

show systemuser \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the system users

## delete systemuser

Use this operation to delete system user(s)

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete systemuser id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the system users

This is a mandatory parameter.

## set systemuser

Use this operation to modify system user

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set systemuser id=&lt;string&gt; \[external\_authentication=(false | true)\] \[name=&lt;string&gt;\] \[session\_timeout=&lt;int&gt;\] \[session\_timeout\_unit=&lt;string&gt;\] \[enable\_session\_timeout=(false | true)\] \[permission=&lt;string&gt;\] \[password=&lt;stringx&gt;\] \[encrypted=(false | true)\] \[groups=&lt;string...&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the system users

This is a mandatory parameter.

**external\_authentication**

Enable external authentication

**name**

User Name

**session\_timeout**

Session timeout for the user

**session\_timeout\_unit**

Session timeout unit for the user

**enable\_session\_timeout**

Enables session timeout for user

**permission**

Actions that this user is authorized to perform

**password**

Password

**encrypted**

Provide encrypted password

**groups**

Groups to which user belongs

## add systemuser

Use this operation to add system user

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add systemuser name=&lt;string&gt; password=&lt;stringx&gt; \[external\_authentication=(false | true)\] \[session\_timeout=&lt;int&gt;\] \[session\_timeout\_unit=&lt;string&gt;\] \[enable\_session\_timeout=(false | true)\] \[permission=&lt;string&gt;\] \[encrypted=(false | true)\] \[groups=&lt;string...&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**name**

User Name

This is a mandatory parameter.

**password**

Password

This is a mandatory parameter.

**external\_authentication**

Enable external authentication

**session\_timeout**

Session timeout for the user

**session\_timeout\_unit**

Session timeout unit for the user

**enable\_session\_timeout**

Enables session timeout for user

**permission**

Actions that this user is authorized to perform

**encrypted**

Provide encrypted password

**groups**

Groups to which user belongs
