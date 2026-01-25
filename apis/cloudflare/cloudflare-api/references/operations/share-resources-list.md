# GET /accounts/{account_id}/shares/{share_id}/resources

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**List share resources by share ID**
**Operation ID:** `share-resources-list`

List share resources by share ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |
| `share_id` | path | resource-sharing_share_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List account share resources response. |
| 4XX | List account share resources response failure. |
| 5XX | List account share resources response failure. |

**Success Response Schema:**

[resource-sharing_share_resource_response_collection](../schemas/resource-sharing/resource-sharing-share-resource-response-collection.md)

## Security

- **api_email**
- **api_key**
