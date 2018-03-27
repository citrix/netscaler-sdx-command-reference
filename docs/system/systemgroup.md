# systemgroup

System Groups

[show](#show%20systemgroup) | [delete](#delete%20systemgroup) | [set](#set%20systemgroup) | [add](#add%20systemgroup)

## show systemgroup

Use this operation to get system groups

## Synopsys 

show systemgroup \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the system groups

## delete systemgroup

Use this operation to delete system group(s)

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

delete systemgroup id=&lt;string&gt;

## Parameters {#parameters-1 style="margin-left: 20px;"}

**id**

Id is system generated key for all the system groups

This is a mandatory parameter.

## set systemgroup

Use this operation to modify system group

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set systemgroup id=&lt;string&gt; \[allow\_application\_only=(false | true)\] \[assign\_all\_apps=(false | true)\] \[name=&lt;string&gt;\] \[role=&lt;string&gt;\] \[session\_timeout=&lt;int&gt;\] \[tenant\_id=&lt;string&gt;\] \[session\_timeout\_unit=&lt;string&gt;\] \[enable\_session\_timeout=(false | true)\] \[permission=&lt;string&gt;\] \[assign\_all\_devices=(false | true)\] \[application\_names\_with\_regex=&lt;string...&gt;\] \[application\_names=&lt;string...&gt;\] \[users=&lt;string...&gt;\] \[standalone\_instances\_id=&lt;string...&gt;\] \[application\_names\_without\_regex=&lt;string...&gt;\] \[roles=&lt;string...&gt;\]

## Parameters {#parameters-2 style="margin-left: 20px;"}

**id**

Id is system generated key for all the system groups

This is a mandatory parameter.

**allow\_application\_only**

Checks if only application centic page is needed

**assign\_all\_apps**

Assign All Applications (YES|NO)

**name**

Group Name

**role**

Role (admin|nonadmin)

**session\_timeout**

Session timeout for the Group

**tenant\_id**

Id of the tenant

**session\_timeout\_unit**

Session timeout unit for the Group

**enable\_session\_timeout**

Enables session timeout for group

**permission**

Permission for the group (admin/read-only)

**assign\_all\_devices**

Assign All Instances (YES|NO)

**application\_names\_with\_regex**

Application names defined with regex that are part of this group

**application\_names**

All Application names that are part of this group.This includes selected appnames as well as applications which are result of defined regex

**users**

Users belong to the group

**standalone\_instances\_id**

Stand alone instances belong to this groupp

**application\_names\_without\_regex**

selected application names that are part of this group

**roles**

Roles assigned to the group

## add systemgroup

Use this operation to add system group

## Synopsys {#synopsys-3 style="margin-left: 20px;"}

add systemgroup name=&lt;string&gt; permission=&lt;string&gt; \[allow\_application\_only=(false | true)\] \[assign\_all\_apps=(false | true)\] \[role=&lt;string&gt;\] \[session\_timeout=&lt;int&gt;\] \[tenant\_id=&lt;string&gt;\] \[session\_timeout\_unit=&lt;string&gt;\] \[enable\_session\_timeout=(false | true)\] \[assign\_all\_devices=(false | true)\] \[application\_names\_with\_regex=&lt;string...&gt;\] \[application\_names=&lt;string...&gt;\] \[users=&lt;string...&gt;\] \[standalone\_instances\_id=&lt;string...&gt;\] \[application\_names\_without\_regex=&lt;string...&gt;\] \[roles=&lt;string...&gt;\]

## Parameters {#parameters-3 style="margin-left: 20px;"}

**name**

Group Name

This is a mandatory parameter.

**permission**

Permission for the group (admin/read-only)

This is a mandatory parameter.

**allow\_application\_only**

Checks if only application centic page is needed

**assign\_all\_apps**

Assign All Applications (YES|NO)

**role**

Role (admin|nonadmin)

**session\_timeout**

Session timeout for the Group

**tenant\_id**

Id of the tenant

**session\_timeout\_unit**

Session timeout unit for the Group

**enable\_session\_timeout**

Enables session timeout for group

**assign\_all\_devices**

Assign All Instances (YES|NO)

**application\_names\_with\_regex**

Application names defined with regex that are part of this group

**application\_names**

All Application names that are part of this group.This includes selected appnames as well as applications which are result of defined regex

**users**

Users belong to the group

**standalone\_instances\_id**

Stand alone instances belong to this groupp

**application\_names\_without\_regex**

selected application names that are part of this group

**roles**

Roles assigned to the group
