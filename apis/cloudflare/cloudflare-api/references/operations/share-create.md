# POST /accounts/{account_id}/shares

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**Create a new share**
**Operation ID:** `share-create`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [resource-sharing_create_share_request](../schemas/resource-sharing/resource-sharing-create-share-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Share created. |
| 4XX | Create share failure. |
| 5XX | Create share failure. |

**Success Response Schema:**

[resource-sharing_share_response_single](../schemas/resource-sharing/resource-sharing-share-response-single.md)

## Security

- **api_email**
- **api_key**
