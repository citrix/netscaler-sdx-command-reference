# nssslcertkeypolicy

NetScaler SSL Cert-Key Polling Policy

[do do\_poll](#do%20nssslcertkeypolicy%20do_poll) | [show](#show%20nssslcertkeypolicy) | [set](#set%20nssslcertkeypolicy)

## do nssslcertkeypolicy do\_poll

Use this operation to poll all SSL certificates from all NetScalers and update the database

## Synopsys 

do nssslcertkeypolicy do\_poll

## show nssslcertkeypolicy

Use this operation to get the polling frequency of the NetScaler SSL certificates

## Synopsys {#synopsys-1 style="margin-left: 20px;"}

show nssslcertkeypolicy

## set nssslcertkeypolicy

Use this operation to set the polling frequency of the NetScaler SSL certificates

## Synopsys {#synopsys-2 style="margin-left: 20px;"}

set nssslcertkeypolicy \[ns\_ip\_address=&lt;ipaddress...&gt;\] \[polling\_interval=&lt;int&gt;\] \[interval\_unit=&lt;string&gt;\]

## Parameters 

**ns\_ip\_address**

List of NetScaler IP Address

**polling\_interval**

Frequency of polling in minutes

**interval\_unit**

Frequency unit (Minutes)
