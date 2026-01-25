# DELETE /rest/api/3/filter/{id}/columns

**Resource:** [Filters](../resources/Filters.md)
**Reset columns**
**Operation ID:** `resetColumns`

Reset the user's column configuration for the filter to the default.

**[Permissions](#permissions) required:** Permission to access Jira, however, columns are only reset for:

 *  filters owned by the user.
 *  filters shared with a group that the user is a member of.
 *  filters shared with a private project that the user has *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for.
 *  filters shared with a public project.
 *  filters shared with the public.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the filter. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if:

 *  the filter is not found.
 *  the user does not have permission to view the filter. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
