# GET /accounts/{account_id}/shares

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**List account shares**
**Operation ID:** `shares-list`

Lists all account shares.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List account shares response. |
| 4XX | List account shares response failure. |
| 5XX | List account shares response failure. |

**Success Response Schema:**

[resource-sharing_share_response_collection](../schemas/resource-sharing/resource-sharing-share-response-collection.md)

## Security

- **api_email**
- **api_key**
