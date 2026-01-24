# GET /v1/fabric/service/integration_config

**Resource:** [fabric](../resources/fabric.md)
**Operation ID:** `GetFabricServiceIntegrationConfig`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `service_name` | query | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[fabric_service](../schemas/fabric/fabric-service.md)

