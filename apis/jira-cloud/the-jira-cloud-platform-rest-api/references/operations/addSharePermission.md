# POST /rest/api/3/filter/{id}/permission

**Resource:** [Filter sharing](../resources/Filter-sharing.md)
**Add share permission**
**Operation ID:** `addSharePermission`

Add a share permissions to a filter. If you add a global share permission (one for all logged-in users or the public) it will overwrite all share permissions for the filter.

Be aware that this operation uses different objects for updating share permissions compared to [Update filter](#api-rest-api-3-filter-id-put).

**[Permissions](#permissions) required:** *Share dashboards and filters* [global permission](https://confluence.atlassian.com/x/x4dKLg) and the user must own the filter.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the filter. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SharePermissionInputBean](../schemas/Share/SharePermissionInputBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if:

 *  the request object is invalid. For example, it contains an invalid type, the ID does not match the type, or the project or group is not found.
 *  the user does not own the filter.
 *  the user does not have the required permissions. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  the filter is not found.
 *  the user does not have permission to view the filter. |

**Success Response Schema:**

Array of [SharePermission](../schemas/Share/SharePermission.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
