---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($requestAdapter);

$requestBody = new ChatMessage();
$body = new ItemBody();
$body->setContentType(new BodyType('html'));

$body->setContent('<emoji alt=\"😶‍🌫️\"></emoji>');


$requestBody->setBody($body);


$requestResult = $graphServiceClient->chatsById('chat-id')->messages()->post($requestBody);


```