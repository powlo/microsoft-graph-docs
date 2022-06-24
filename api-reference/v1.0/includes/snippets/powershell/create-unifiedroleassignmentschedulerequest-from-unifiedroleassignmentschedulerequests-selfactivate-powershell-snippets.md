---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.DeviceManagement.Enrolment

$params = @{
	Action = "selfActivate"
	PrincipalId = "071cc716-8147-4397-a5ba-b2105951cc0b"
	RoleDefinitionId = "8424c6f0-a189-499e-bbd0-26c1753c96d4"
	DirectoryScopeId = "/"
	Justification = "I need access to the Attribute Administrator role to manage attributes to be assigned to restricted AUs"
	ScheduleInfo = @{
		StartDateTime = [System.DateTime]::Parse("2022-04-14T00:00:00.000Z")
		Expiration = @{
			Type = "AfterDuration"
			Duration = "PT5H"
		}
	}
	TicketInfo = @{
		TicketNumber = "CONTOSO:Normal-67890"
		TicketSystem = "MS Project"
	}
}

New-MgRoleManagementDirectoryRoleAssignmentScheduleRequest -BodyParameter $params

```