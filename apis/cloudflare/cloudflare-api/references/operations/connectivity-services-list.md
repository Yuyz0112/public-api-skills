# GET /accounts/{account_id}/connectivity/directory/services

**Resource:** [Connectivity Services](../resources/Connectivity-Services.md)
**List connectivity services**
**Operation ID:** `connectivity-services-list`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | infra_AccountTag | Yes |  |
| `type` | query | string | No |  |
| `page` | query | integer (int32) | No | Current page in the response |
| `per_page` | query | integer (int32) | No | Max amount of entries returned per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved connectivity services |
| 4XX | Failed to retrieve connectivity services |

## Security

- **api_email**
- **api_key**
- **api_token**
