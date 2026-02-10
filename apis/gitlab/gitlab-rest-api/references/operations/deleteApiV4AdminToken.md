# DELETE /api/v4/admin/token

**Resource:** [Admin](../resources/Admin.md)
**Revoke a token.**
**Operation ID:** `deleteApiV4AdminToken`

This feature was introduced in GitLab 17.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | The token that information is requested about. |

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 422 | Unprocessable |

