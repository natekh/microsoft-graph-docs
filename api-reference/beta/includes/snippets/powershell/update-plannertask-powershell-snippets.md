---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Planner

$params = @{
	Assignments = @{
		"Fbab97d0-4932-4511-b675-204639209557" = @{
			"@odata.type" = "#microsoft.graph.plannerAssignment"
			OrderHint = "N9917 U2883!"
		}
	}
	AppliedCategories = @{
		Category3 = $true
		Category4 = $false
	}
	Recurrence = @{
		Schedule = @{
			Pattern = @{
				Type = "daily"
				Interval = 3
			}
			PatternStartDateTime = [System.DateTime]::Parse("2022-02-22T02:10:33Z")
		}
	}
}

Update-MgPlannerTask -PlannerTaskId $plannerTaskId -BodyParameter $params-If-Match W/"JzEtVGFzayAgQEBAQEBAQEBAQEBAQEBAWCc=" 


```