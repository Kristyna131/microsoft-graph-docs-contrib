---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Groups

$params = @{
	displayName = "New Managers March 2024"
	description = "New Managers training course for March 2024"
	groupTypes = @(
		"Unified"
	)
	mailEnabled = $true
	mailNickname = "newMan202403"
	securityEnabled = $false
}

New-MgGroup -BodyParameter $params

```