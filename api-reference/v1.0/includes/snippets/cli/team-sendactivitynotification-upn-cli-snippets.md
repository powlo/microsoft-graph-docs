---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc teams send-activity-notification post --team-id {team-id} --body '{\
    "topic": {\
        "source": "entityUrl",\
        "value": "https://graph.microsoft.com/v1.0/teams/{teamId}/channels/{channelId}/tabs/{tabId}"\
    },\
    "activityType": "reservationUpdated",\
    "previewText": {\
        "content": "You have moved up the queue"\
    },\
    "recipient": {\
        "@odata.type": "microsoft.graph.aadUserNotificationRecipient",\
        "userId": "jacob@contoso.com"\
    },\
    "templateParameters": [\
        {\
            "name": "reservationId",\
            "value": "TREEE433"\
        },\
        {\
            "name": "currentSlot",\
            "value": "23"\
        }\
    ]\
}\
'

```