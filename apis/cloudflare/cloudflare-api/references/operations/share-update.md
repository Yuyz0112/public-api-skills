# PUT /accounts/{account_id}/shares/{share_id}

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**Update a share**
**Operation ID:** `share-update`

Updating is not immediate, an updated share object with a new status will be returned.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |
| `share_id` | path | resource-sharing_share_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [resource-sharing_update_share_request](../schemas/resource-sharing/resource-sharing-update-share-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Share updated. |
| 4XX | Update share failure. |
| 5XX | Update share failure. |

**Success Response Schema:**

[resource-sharing_share_response_single](../schemas/resource-sharing/resource-sharing-share-response-single.md)

## Security

- **api_email**
- **api_key**
