---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

ISiteUsageStorageCollectionPage getOneDriveUsageStorage = graphClient.reports()
	.getOneDriveUsageStorage("D7")
	.buildRequest()
	.get();

```