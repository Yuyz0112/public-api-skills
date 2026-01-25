# PUT /accounts/{account_id}/connectivity/directory/services/{service_id}

**Resource:** [Connectivity Services](../resources/Connectivity-Services.md)
**Update connectivity service**
**Operation ID:** `connectivity-services-put`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `service_id` | path | string (uuid) | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [infra_ServiceConfig](../schemas/infra/infra-ServiceConfig.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully updated connectivity service |
| 4XX | Failed to update connectivity service |

## Security

- **api_email**
- **api_key**
- **api_token**
