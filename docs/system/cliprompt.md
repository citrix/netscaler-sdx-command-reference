# cliprompt

CLI Prompt string

## set cliprompt

Use this operation to set CLI prompt

## Synopsys 

set cliprompt promptString=&lt;string&gt;

## Parameters 

**promptString**

The prompt string. The following special values are allowed: %! -  will be replaced by the history event number %u -  will be replaced by the NetScaler SVM user name %h -  will be replaced by the NetScaler SVM hostname %t -  will be replaced by the current time (12 hr) %T -  will be replaced by the current time (24 hr) %d -  will be replaced by the current date (yy/mm/dd) This is a mandatory argument.

This is a mandatory parameter.
