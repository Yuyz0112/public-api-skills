# GET /organizations/{organization_id}/shares

**Resource:** [Resource Sharing](../resources/Resource-Sharing.md)
**List organization shares**
**Operation ID:** `organization-shares-list`

Lists all organization shares.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | path | resource-sharing_organization_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List organization shares response. |
| 4XX | List organization shares response failure. |
| 5XX | List organization shares response failure. |

**Success Response Schema:**

[resource-sharing_share_response_collection](../schemas/resource-sharing/resource-sharing-share-response-collection.md)

## Security

- **api_email**
- **api_key**
