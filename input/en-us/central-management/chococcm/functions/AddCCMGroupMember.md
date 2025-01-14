---
Order: 20
xref: add-ccmgroupmember
Title: Add-CCMGroupMember
Description: Information about the Add-CCMGroupMember function
RedirectFrom: docs/add-ccmgroup-member
---

# Add-CCMGroupMember

<!-- This documentation is automatically generated from /Add-CCMGroupMember.ps1 using GenerateDocs.ps1. Contributions are welcome at the original location(s). -->

Adds a member to an existing Group in Central Management

## Syntax

~~~powershell
Add-CCMGroupMember `
  [-Name <String>] `
  [-Group <String[]>] [<CommonParameters>]
~~~


~~~powershell
Add-CCMGroupMember `
  [-Name <String>] `
  -Computer <String[]> [<CommonParameters>]
~~~

## Description

Add new computers and groups to existing Central Management Groups


## Aliases

None

## Examples

 **EXAMPLE 1**

~~~powershell
Add-CCMGroupMember -Group 'Newly Imaged' -Computer Lab1,Lab2,Lab3

~~~

## Inputs

None

## Outputs

None

## Parameters

###  -Name &lt;String&gt;
The group to edit

Property               | Value
---------------------- | -----
Aliases                |
Required?              | true
Position?              | named
Default Value          |
Accept Pipeline Input? | false

###  -Computer &lt;String[]&gt;
The computer(s) to add

Property               | Value
---------------------- | -----
Aliases                |
Required?              | true
Position?              | named
Default Value          |
Accept Pipeline Input? | false

###  -Group [&lt;String[]&gt;]
The group(s) to add

Property               | Value
---------------------- | -----
Aliases                |
Required?              | false
Position?              | named
Default Value          |
Accept Pipeline Input? | false

### &lt;CommonParameters&gt;

This cmdlet supports the common parameters: -Verbose, -Debug, -ErrorAction, -ErrorVariable, -OutBuffer, and -OutVariable. For more information, see `about_CommonParameters` https://go.microsoft.com/fwlink/p/?LinkID=113216 .



[Function Reference](xref:chococcm-functions)

> :memo: **NOTE** This documentation has been automatically generated from `Import-Module "ChocoCCM" -Force; Get-Help Add-CCMGroupMember -Full`.
