# GET /accounts/{account_id}/shares/{share_id}/recipients/{recipient_id}

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**Get share recipient by ID**
**Operation ID:** `share-recipients-get-by-id`

Get share recipient by ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |
| `share_id` | path | resource-sharing_share_id | Yes |  |
| `recipient_id` | path | resource-sharing_recipient_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get account share recipient response. |
| 4XX | Get account share recipient response failure. |
| 5XX | Get account share recipient response failure. |

**Success Response Schema:**

[resource-sharing_share_recipient_response_single](../schemas/resource-sharing/resource-sharing-share-recipient-response-single.md)

## Security

- **api_email**
- **api_key**
