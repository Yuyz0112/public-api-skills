# GET /accounts/{account_id}/connectivity/directory/services/{service_id}

**Resource:** [Connectivity Services](../resources/Connectivity-Services.md)
**Get connectivity service**
**Operation ID:** `connectivity-services-get`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `service_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved connectivity service |
| 4XX | Failed to retrieve connectivity service |

## Security

- **api_email**
- **api_key**
- **api_token**
