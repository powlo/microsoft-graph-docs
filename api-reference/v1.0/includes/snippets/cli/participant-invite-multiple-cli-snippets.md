---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc communications calls participants invite post --call-id {call-id} --body '{\
  "participants": [\
    {\
      "@odata.type": "#microsoft.graph.invitationParticipantInfo",\
      "replacesCallId": "a7ebfb2d-871e-419c-87af-27290b22e8db",\
      "identity": {\
        "@odata.type": "#microsoft.graph.identitySet",\
        "user": {\
          "@odata.type": "#microsoft.graph.identity",\
          "id": "7e1b4346-85a6-4bdd-abe3-d11c5d420efe",\
          "displayName": "string"\
        }\
      }\
    },\
    {\
      "@odata.type": "#microsoft.graph.invitationParticipantInfo",\
      "replacesCallId": "a7ebfb2d-871e-419c-87af-27290b22e8db",\
      "identity": {\
        "@odata.type": "#microsoft.graph.identitySet",\
        "user": {\
          "@odata.type": "#microsoft.graph.identity",\
          "id": "1e126418-44a0-4a94-a6f8-0efe1ad71acb",\
          "displayName": "string"\
        }\
      }\
    }\
  ],\
  "clientContext": "f2fa86af-3c51-4bc2-8fc0-475452d9764f"\
}\
'

```