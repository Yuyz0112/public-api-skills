# PUT /accounts/{account_id}/shares/{share_id}/resources/{resource_id}

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**Update a share resource**
**Operation ID:** `share-resource-update`

Update is not immediate, an updated share resource object with a new status will be returned.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | resource-sharing_account_id | Yes |  |
| `share_id` | path | resource-sharing_share_id | Yes |  |
| `resource_id` | path | resource-sharing_resource_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [resource-sharing_update_share_resource_request](../schemas/resource-sharing/resource-sharing-update-share-resource-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Share resource updated. |
| 4XX | Update share resource failure. |
| 5XX | Update share resource failure. |

**Success Response Schema:**

[resource-sharing_share_resource_response_single](../schemas/resource-sharing/resource-sharing-share-resource-response-single.md)

## Security

- **api_email**
- **api_key**
