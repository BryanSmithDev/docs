---
Order: 150
xref: get-ccmoutdatedsoftwarereportdetail
Title: Get-CCMOutdatedSoftwareReportDetail
Description: Information about the Get-CCMOutdatedSoftwareReportDetail function
RedirectFrom: docs/get-ccmoutdated-software-report-detail
---

# Get-CCMOutdatedSoftwareReportDetail

<!-- This documentation is automatically generated from /Get-CCMOutdatedSoftwareReportDetail.ps1 using GenerateDocs.ps1. Contributions are welcome at the original location(s). -->

View detailed information about an Outdated Software Report

## Syntax

~~~powershell
Get-CCMOutdatedSoftwareReportDetail `
  -Report <String> [<CommonParameters>]
~~~

## Description

Return report details from an Outdated Software Report in Central Management


## Aliases

None

## Examples

 **EXAMPLE 1**

~~~powershell
Get-CCMOutdatedSoftwareReportDetail -Report '7/4/2020 6:44:40 PM'

~~~

## Inputs

None

## Outputs

None

## Parameters

###  -Report &lt;String&gt;
The report to query

Property               | Value
---------------------- | -----
Aliases                |
Required?              | true
Position?              | 1
Default Value          |
Accept Pipeline Input? | false

### &lt;CommonParameters&gt;

This cmdlet supports the common parameters: -Verbose, -Debug, -ErrorAction, -ErrorVariable, -OutBuffer, and -OutVariable. For more information, see `about_CommonParameters` https://go.microsoft.com/fwlink/p/?LinkID=113216 .



[Function Reference](xref:chococcm-functions)

> :memo: **NOTE** This documentation has been automatically generated from `Import-Module "ChocoCCM" -Force; Get-Help Get-CCMOutdatedSoftwareReportDetail -Full`.
