---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($requestAdapter);

$requestBody = new PrivilegedRoleAssignment();
$requestBody->setUserId('userId-value');

$requestBody->setRoleId('roleId-value');



$requestResult = $graphServiceClient->privilegedRoleAssignments()->post($requestBody);


```