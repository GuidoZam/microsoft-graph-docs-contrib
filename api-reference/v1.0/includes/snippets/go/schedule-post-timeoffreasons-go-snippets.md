---
description: "Automatically generated file. DO NOT MODIFY"
---

```go


// Code snippets are only available for the latest major version. Current major version is $v1.*

// Dependencies
import (
	  "context"
	  msgraphsdk "github.com/microsoftgraph/msgraph-sdk-go"
	  graphmodels "github.com/microsoftgraph/msgraph-sdk-go/models"
	  //other-imports
)

requestBody := graphmodels.NewTimeOffReason()
displayName := "Vacation"
requestBody.SetDisplayName(&displayName) 
iconType := graphmodels.PLANE_TIMEOFFREASONICONTYPE 
requestBody.SetIconType(&iconType) 
isActive := true
requestBody.SetIsActive(&isActive) 
code := "VacationCode"
requestBody.SetCode(&code) 

// To initialize your graphClient, see https://learn.microsoft.com/en-us/graph/sdks/create-client?from=snippets&tabs=go
timeOffReasons, err := graphClient.Teams().ByTeamId("team-id").Schedule().TimeOffReasons().Post(context.Background(), requestBody, nil)


```