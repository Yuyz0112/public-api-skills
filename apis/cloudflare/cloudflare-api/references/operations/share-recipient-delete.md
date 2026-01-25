# DELETE /accounts/{account_id}/shares/{share_id}/recipients/{recipient_id}

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**Delete a share recipient**
**Operation ID:** `share-recipient-delete`

Deletion is not immediate, an updated share recipient object with a new status will be returned.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |
| `share_id` | path | resource-sharing_share_id | Yes |  |
| `recipient_id` | path | resource-sharing_recipient_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Share recipient deleted. |
| 4XX | Delete share recipient failure. |
| 5XX | Delete share recipient failure. |

**Success Response Schema:**

[resource-sharing_share_recipient_response_single](../schemas/resource-sharing/resource-sharing-share-recipient-response-single.md)

## Security

- **api_email**
- **api_key**
