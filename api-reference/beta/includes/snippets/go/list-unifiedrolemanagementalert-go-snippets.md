---
description: "Automatically generated file. DO NOT MODIFY"
---

```go


import (
	  "context"
	  msgraphsdk "github.com/microsoftgraph/msgraph-beta-sdk-go"
	  graphidentitygovernance "github.com/microsoftgraph/msgraph-beta-sdk-go/identitygovernance"
	  //other-imports
)

graphClient := msgraphsdk.NewGraphServiceClientWithCredentials(cred, scopes)



requestFilter := "scopeId eq '/' and scopeType eq 'DirectoryRole'"

requestParameters := &graphidentitygovernance.IdentityGovernanceRoleManagementAlertsAlertsRequestBuilderGetQueryParameters{
	Filter: &requestFilter,
	Expand: [] string {"alertDefinition","alertConfiguration","alertIncidents"},
}
configuration := &graphidentitygovernance.IdentityGovernanceRoleManagementAlertsAlertsRequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}

result, err := graphClient.IdentityGovernance().RoleManagementAlerts().Alerts().Get(context.Background(), configuration)


```