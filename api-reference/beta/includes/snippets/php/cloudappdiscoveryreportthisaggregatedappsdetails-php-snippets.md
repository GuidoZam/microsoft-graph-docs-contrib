---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php
use Microsoft\Graph\Beta\GraphServiceClient;


$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);


$result = $graphServiceClient->security()->dataDiscovery()->cloudAppDiscovery()->uploadedStreams()->byCloudAppDiscoveryReportId('cloudAppDiscoveryReport-id')->microsoftGraphSecurityAggregatedAppsDetailsWithPeriod(new \DateInterval('{period}'))->get()->wait();

```