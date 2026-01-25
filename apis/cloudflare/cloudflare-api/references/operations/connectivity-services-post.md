# POST /accounts/{account_id}/connectivity/directory/services

**Resource:** [Connectivity Services](../resources/Connectivity-Services.md)
**Create connectivity service**
**Operation ID:** `connectivity-services-post`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | infra_AccountTag | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [infra_ServiceConfig](../schemas/infra/infra-ServiceConfig.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully created connectivity service |
| 4XX | Failed to create connectivity service |

## Security

- **api_email**
- **api_key**
- **api_token**
