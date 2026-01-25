# GET /rest/atlassian-connect/1/service-registry

**Resource:** [Service Registry](../resources/Service-Registry.md)
**Retrieve the attributes of service registries**
**Operation ID:** `ServiceRegistryResource.services_get`

Retrieve the attributes of given service registries.

**[Permissions](#permissions) required:** Only Connect apps can make this request and the servicesIds belong to the tenant you are requesting

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `serviceIds` | query | string[] | Yes | The ID of the services (the strings starting with "b:" need to be decoded in Base64). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | The request needs to be authenticated. |
| 403 | The request isn't authorized. |
| 500 | The endpoint failed internally. |
| 501 | The endpoint isn't ready for receiving requests. |
| 504 | The upstream service is busy. |

**Success Response Schema:**

Array of [ServiceRegistry](../schemas/Service/ServiceRegistry.md)

