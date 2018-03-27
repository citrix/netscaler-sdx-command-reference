# configJob

Configuration Job

[show](#show%20configJob) | [add](#add%20configJob)

## show configJob

Use this operation to get config job

## Synopsys 

show configJob \[id=&lt;string&gt;\]

## Parameters 

**id**

Id is system generated key for all the configuration jobs

## add configJob

Use this operation to run config job

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

add configJob \[execute\_username=&lt;string&gt;\] \[nextScheduleTimeEpoch=&lt;string&gt;\] \[template\_info=&lt;configuration\_template&gt;\] \[node\_id=&lt;string&gt;\] \[timestamp=&lt;int&gt;\] \[scheduleType=&lt;string&gt;\] \[on\_error=&lt;string&gt;\] \[lastExecutedTimeEpoch=&lt;string&gt;\] \[name=&lt;string&gt;\] \[scheduleTimes=&lt;string&gt;\] \[device\_groups=&lt;string...&gt;\] \[sms\_profiles=&lt;string&gt;\] \[device\_family=&lt;string&gt;\] \[tz\_offset=&lt;int&gt;\] \[status=&lt;string&gt;\] \[execute\_password=&lt;stringx&gt;\] \[variables=&lt;variable\_values...&gt;\] \[devices\_db=&lt;string&gt;\] \[execute\_sequentially=(false | true)\] \[scheduleOptions=&lt;string&gt;\] \[scheduleTimesEpoch=&lt;string&gt;\] \[device\_groups\_db=&lt;string&gt;\] \[mail\_profiles=&lt;string&gt;\] \[lastExecutionStatus=&lt;string&gt;\] \[devices=&lt;ipaddress...&gt;\] \[credentials\_required=(false | true)\] \[preview\_rollback\_commands=&lt;string...&gt;\] \[devices\_completed\_count=&lt;int&gt;\] \[devices\_count=&lt;int&gt;\] \[preview\_commands=&lt;string...&gt;\]

## Parameters {#parameters-1 style="margin-left: 20px;"}

**execute\_username**

Execute User Name for job

**nextScheduleTimeEpoch**

Schedule time epoch at which job is scheduled to be run next.

**template\_info**

Configuration Template to be executed/scheduled

**node\_id**

Node id of the node executing the task in a Multinode / HA deployment

**timestamp**

Time of Creation of Configuration Job

**scheduleType**

Schedule Type of Configuration Template that is scheduled

**on\_error**

Behaviour on encountering error while applying configuration template on a device: CONTINUE|EXIT|ROLLBACK

**lastExecutedTimeEpoch**

Schedule time epoch at which job was last executed.

**name**

Name of configuration job

**scheduleTimes**

Comma Seperated times of the day(HH:MM) on which Configuration Template is scheduled

**device\_groups**

Device Group Array on which for which job is run

**sms\_profiles**

Comma seperated list of SMS profiles

**device\_family**

Family of Devices for which config job was executed

**tz\_offset**

Time zone offset.

**status**

Status of Config Job

**execute\_password**

Execute Password for job

**variables**

Values of Variables used in commands of the configuration template

**devices\_db**

Device IP Address List Comma Seperated on which job is run

**execute\_sequentially**

True if configuration template is to be applied to devices sequentially

**scheduleOptions**

Comma Seperated Options for scheduling Configuration Template

**scheduleTimesEpoch**

Schedule time epoch (string representation of 11 digit numbers).

**device\_groups\_db**

Device Groups List Comma Seperated on which job is run

**mail\_profiles**

Comma seperated list of Mail profiles

**lastExecutionStatus**

Status of last Execution of Config Job

**devices**

Device IP Address Array on which job is run

**credentials\_required**

True if username/password need to be asked before configuration template is to applied on devices

**preview\_rollback\_commands**

Preview of list of rollback commands

**devices\_completed\_count**

Devices Completed Count

**devices\_count**

Number of Devices on which commands executed

**preview\_commands**

Preview of list of commands
