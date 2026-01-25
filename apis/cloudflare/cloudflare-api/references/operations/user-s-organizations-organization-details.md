# GET /user/organizations/{organization_id}

**Resource:** [User's Organizations](../resources/User-s-Organizations.md)
**Organization Details**
**Operation ID:** `user'-s-organizations-organization-details`
⚠️ **Deprecated**

Gets a specific organization the user is associated with.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | path | iam_common_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Organization Details response |
| 4XX | Organization Details response failure |

**Success Response Schema:**

[iam_single_organization_response](../schemas/iam/iam-single-organization-response.md)

## Security

- **api_email**
- **api_key**
