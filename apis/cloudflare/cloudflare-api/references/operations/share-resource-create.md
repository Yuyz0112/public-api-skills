# POST /accounts/{account_id}/shares/{share_id}/resources

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**Create a new share resource**
**Operation ID:** `share-resource-create`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |
| `share_id` | path | resource-sharing_share_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [resource-sharing_create_share_resource_request](../schemas/resource-sharing/resource-sharing-create-share-resource-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Share resource created. |
| 4XX | Create share resource failure. |
| 5XX | Create share resource failure. |

**Success Response Schema:**

[resource-sharing_share_resource_response_single](../schemas/resource-sharing/resource-sharing-share-resource-response-single.md)

## Security

- **api_email**
- **api_key**
