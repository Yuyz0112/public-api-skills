# DELETE /accounts/{account_id}/shares/{share_id}

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**Delete a share**
**Operation ID:** `share-delete`

Deletion is not immediate, an updated share object with a new status will be returned.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |
| `share_id` | path | resource-sharing_share_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Share deleted. |
| 4XX | Delete share failure. |
| 5XX | Delete share failure. |

**Success Response Schema:**

[resource-sharing_share_response_single](../schemas/resource-sharing/resource-sharing-share-response-single.md)

## Security

- **api_email**
- **api_key**
