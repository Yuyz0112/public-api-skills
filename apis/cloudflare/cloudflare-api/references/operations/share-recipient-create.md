# POST /accounts/{account_id}/shares/{share_id}/recipients

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**Create a new share recipient**
**Operation ID:** `share-recipient-create`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |
| `share_id` | path | resource-sharing_share_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [resource-sharing_create_share_recipient_request](../schemas/resource-sharing/resource-sharing-create-share-recipient-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Share recipient created. |
| 4XX | Create share recipient failure. |
| 5XX | Create share recipient failure. |

**Success Response Schema:**

[resource-sharing_share_recipient_response_single](../schemas/resource-sharing/resource-sharing-share-recipient-response-single.md)

## Security

- **api_email**
- **api_key**
