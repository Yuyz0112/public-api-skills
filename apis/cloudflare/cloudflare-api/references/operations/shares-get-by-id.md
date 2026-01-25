# GET /accounts/{account_id}/shares/{share_id}

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**Get account share by ID**
**Operation ID:** `shares-get-by-id`

Fetches share by ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |
| `share_id` | path | resource-sharing_share_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get account share response. |
| 4XX | Get account share response failure. |
| 5XX | Get account share response failure. |

**Success Response Schema:**

[resource-sharing_share_response_single](../schemas/resource-sharing/resource-sharing-share-response-single.md)

## Security

- **api_email**
- **api_key**
