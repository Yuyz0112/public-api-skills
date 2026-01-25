# GET /accounts/{account_id}/shares/{share_id}/resources/{resource_id}

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**Get share resource by ID**
**Operation ID:** `share-resources-get-by-id`

Get share resource by ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |
| `share_id` | path | resource-sharing_share_id | Yes |  |
| `resource_id` | path | resource-sharing_resource_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get account share resource response. |
| 4XX | Get account share resource response failure. |
| 5XX | Get account share resource response failure. |

**Success Response Schema:**

[resource-sharing_share_resource_response_single](../schemas/resource-sharing/resource-sharing-share-resource-response-single.md)

## Security

- **api_email**
- **api_key**
