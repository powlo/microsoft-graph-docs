---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($requestAdapter);


$requestResult = $graphServiceClient->me()->tasks()->listsById('baseTaskList-id')->tasksById('baseTask-id')->checklistItemsById('checklistItem-id')->get();


```