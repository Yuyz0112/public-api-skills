# DELETE /user/organizations/{organization_id}

**Resource:** [User's Organizations](../resources/User-s-Organizations.md)
**Leave Organization**
**Operation ID:** `user'-s-organizations-leave-organization`
⚠️ **Deprecated**

Removes association to an organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `organization_id` | path | iam_common_components-schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Leave Organization response |
| 4XX | Leave Organization response failure |

## Security

- **api_email**
- **api_key**
