---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(credentials, scopes)


request_configuration = JobsRequestBuilder.JobsRequestBuilderGetRequestConfiguration(
headers = {
		'Authorization' : "Bearer {Token}",
}

)

result = await graph_client.service_principals.by_service_principal_id('servicePrincipal-id').synchronization.jobs.get(request_configuration = request_configuration)


```