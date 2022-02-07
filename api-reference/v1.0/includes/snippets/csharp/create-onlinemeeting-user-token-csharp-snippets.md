---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

//To override onlineMeeting Properties, like For E.g. You need to disable the chat for this OnlineMeeting.
 IDictionary<string, object> additionalData = new Dictionary<string, object>();
 additionalData.Add("allowMeetingChat", "disabled");
                  

var onlineMeeting = new OnlineMeeting
{
	StartDateTime = DateTimeOffset.Parse("2019-07-12T21:30:34.2444915+00:00"),
	EndDateTime = DateTimeOffset.Parse("2019-07-12T22:00:34.2464912+00:00"),
	Subject = "User Token Meeting",
	AdditionalData = additionalData
};

await graphClient.Me.OnlineMeetings
	.Request()
	.AddAsync(onlineMeeting);

```
