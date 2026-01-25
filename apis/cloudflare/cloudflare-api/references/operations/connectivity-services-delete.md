# DELETE /accounts/{account_id}/connectivity/directory/services/{service_id}

**Resource:** [Connectivity Services](../resources/Connectivity-Services.md)
**Delete connectivity service**
**Operation ID:** `connectivity-services-delete`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `service_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted connectivity service |
| 4XX | Failed to delete connectivity service |

## Security

- **api_email**
- **api_key**
- **api_token**
