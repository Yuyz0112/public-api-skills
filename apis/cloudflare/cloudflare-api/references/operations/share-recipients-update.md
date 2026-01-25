# PUT /accounts/{account_id}/shares/{share_id}/recipients

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**Update a share's recipients**
**Operation ID:** `share-recipients-update`

Changes a share's recipients to match the given list. Returns an error if the share targets an organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |
| `share_id` | path | resource-sharing_share_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [resource-sharing_update_share_recipients_request](../schemas/resource-sharing/resource-sharing-update-share-recipients-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Empty body |
| 4XX | Update share recipients failure. |
| 5XX | Update share recipients failure. |

## Security

- **api_email**
- **api_key**
