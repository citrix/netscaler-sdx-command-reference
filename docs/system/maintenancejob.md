# maintenanceJob

Maintenance Job

[show](#show%20maintenanceJob) | [add](#add%20maintenanceJob)

## show maintenanceJob

Use this operation to get config job

## Synopsys 

show maintenanceJob \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the maintenance jobs

## add maintenanceJob

Use this operation to run config job

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

add maintenanceJob \[device\_family=&lt;string&gt;\] \[status=&lt;string&gt;\] \[task\_name=&lt;string&gt;\] \[resource=&lt;string&gt;\] \[timestamp=&lt;int&gt;\] \[resource\_object=&lt;string&gt;\] \[scheduleTimesEpoch=&lt;string&gt;\] \[name=&lt;string&gt;\] \[mail\_profiles=&lt;string&gt;\] \[action=&lt;string&gt;\] \[devices\_completed\_count=&lt;int&gt;\] \[devices\_count=&lt;int&gt;\] \[scheduleTime=&lt;string&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**device\_family**

Family of Devices for which config job was executed

**status**

Status of Config Job

**task\_name**

task name.

**resource**

resource name.

**timestamp**

Time of Creation of Maintenance Job

**resource\_object**

Object resource payload.

**scheduleTimesEpoch**

Schedule time epoch (string representation of 11 digit numbers).

**name**

Name of maintenance job

**mail\_profiles**

Comma seperated list of Mail profiles

**action**

Schedule time epoch (string representation of 11 digit numbers).

**devices\_completed\_count**

Devices Completed Count

**devices\_count**

Number of Devices on which commands executed

**scheduleTime**

Comma Seperated times of the day(DD:HH:MM) on which Configuration Template is scheduled
