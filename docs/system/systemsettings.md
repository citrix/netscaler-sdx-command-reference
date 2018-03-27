# systemsettings

System Settings

[show](#show%20systemsettings) | [set](#set%20systemsettings)

## show systemsettings

Use this operation to get system settings

## Synopsys 

show systemsettings \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key

## set systemsettings

Use this operation to modify system settings

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

set systemsettings \[enable\_certificate\_download=(false | true)\] \[session\_timeout=&lt;int&gt;\] \[enable\_shell\_access=(false | true)\] \[enable\_session\_timeout=(false | true)\] \[basicauth=(false | true)\] \[svm\_ns\_comm=&lt;string&gt;\] \[is\_metering\_enabled=(false | true)\] \[secure\_access\_only=(false | true)\] \[enable\_nsrecover\_login=(false | true)\] \[session\_timeout\_unit=&lt;string&gt;\] \[act\_id=&lt;string&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**enable\_certificate\_download**

Enable Certificate Download

**session\_timeout**

Session timeout for the system

**enable\_shell\_access**

Enable Shell access for non-nsroot User(s)

**enable\_session\_timeout**

Enables session timeout feature

**basicauth**

Allow Basic Authentication Protocol

**svm\_ns\_comm**

Communication with Instances

**is\_metering\_enabled**

Enable Metering for NS VPX's on SDX

**secure\_access\_only**

Secure Access only

**enable\_nsrecover\_login**

This setting enalbes nsrecover login for SVM

**session\_timeout\_unit**

Session timeout unit for the system

**act\_id**

Activity Id
