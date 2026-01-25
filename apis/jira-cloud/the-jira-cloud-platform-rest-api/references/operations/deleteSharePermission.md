# DELETE /rest/api/3/filter/{id}/permission/{permissionId}

**Resource:** [Filter sharing](../resources/Filter-sharing.md)
**Delete share permission**
**Operation ID:** `deleteSharePermission`

Deletes a share permission from a filter.

**[Permissions](#permissions) required:** Permission to access Jira and the user must own the filter.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the filter. |
| `permissionId` | path | integer (int64) | Yes | The ID of the share permission. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  the filter is not found.
 *  the user does not own the filter. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
