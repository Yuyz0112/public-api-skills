# GET /user/organizations

**Resource:** [User's Organizations](../resources/User-s-Organizations.md)
**List Organizations**
**Operation ID:** `user'-s-organizations-list-organizations`
⚠️ **Deprecated**

Lists organizations the user is associated with.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | iam_schemas-name | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `order` | query | enum: id, name, status | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `match` | query | enum: any, all | No |  |
| `status` | query | enum: member, invited | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Organizations response |
| 4XX | List Organizations response failure |

**Success Response Schema:**

[iam_collection_organization_response](../schemas/iam/iam-collection-organization-response.md)

## Security

- **api_email**
- **api_key**
