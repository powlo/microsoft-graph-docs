---
description: "Automatically generated file. DO NOT MODIFY"
---

```go


import (
	  "context"
	  msgraphsdk "github.com/microsoftgraph/msgraph-beta-sdk-go"
	  graphmodels "github.com/microsoftgraph/msgraph-beta-sdk-go/models"
	  //other-imports
)

graphClient := msgraphsdk.NewGraphServiceClientWithCredentials(cred, scopes)


requestBody := graphmodels.NewCalendarGroup()
name := "name-value"
requestBody.SetName(&name) 

result, err := graphClient.Me().CalendarGroups().ByCalendarGroupId("calendarGroup-id").Patch(context.Background(), requestBody, nil)


```