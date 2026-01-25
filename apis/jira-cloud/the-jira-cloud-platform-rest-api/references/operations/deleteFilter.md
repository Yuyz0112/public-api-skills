# DELETE /rest/api/3/filter/{id}

**Resource:** [Filters](../resources/Filters.md)
**Delete filter**
**Operation ID:** `deleteFilter`

Delete a filter.

**[Permissions](#permissions) required:** Permission to access Jira, however filters can only be deleted by the creator of the filter or a user with *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the filter to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the filter is not found. |
| 401 | Returned if the user does not have permission to delete the filter. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
