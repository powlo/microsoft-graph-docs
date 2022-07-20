---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($requestAdapter);

$requestConfiguration = new ChatRequestBuilderGetRequestConfiguration();

$queryParameters = new ChatRequestBuilderGetQueryParameters();
$queryParameters->expand = ["members"];

$requestConfiguration->queryParameters = $queryParameters;


$requestResult = $graphServiceClient->chatsById('chat-id')->get($requestConfiguration);


```