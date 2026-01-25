# GET /accounts/{account_id}/shares/{share_id}/recipients

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**List share recipients by share ID**
**Operation ID:** `share-recipients-list`

List share recipients by share ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |
| `share_id` | path | resource-sharing_share_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List account share recipients response. |
| 4XX | List account share recipients response failure. |
| 5XX | List account share recipients response failure. |

**Success Response Schema:**

[resource-sharing_share_recipient_response_collection](../schemas/resource-sharing/resource-sharing-share-recipient-response-collection.md)

## Security

- **api_email**
- **api_key**
