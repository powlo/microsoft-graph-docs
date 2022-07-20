---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($requestAdapter);

$requestBody = new ItemPublication();
$requestBody->setDescription('One persons journey to the top of the branding management field.');

$requestBody->setDisplayName('Got Brands? The story of Innocenty Popov and his journey to the top.');

$requestBody->setPublishedDate('Date');

$requestBody->setPublisher('International Association of Branding Management Publishing');

$requestBody->setThumbnailUrl('https://iabm.io/sdhdfhsdhshsd.jpg');

$requestBody->setWebUrl('https://www.iabm.io');



$requestResult = $graphServiceClient->me()->profile()->publications()->post($requestBody);


```