---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Solutions.BookingBusinesses["{bookingBusiness-id}"].Services["{bookingService-id}"]
	.Request()
	.DeleteAsync();

```