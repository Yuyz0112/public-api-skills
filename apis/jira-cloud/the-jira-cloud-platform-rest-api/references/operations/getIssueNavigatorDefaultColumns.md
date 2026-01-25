# GET /rest/api/3/settings/columns

**Resource:** [Issue navigator settings](../resources/Issue-navigator-settings.md)
**Get issue navigator default columns**
**Operation ID:** `getIssueNavigatorDefaultColumns`

Returns the default issue navigator columns.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

Array of [ColumnItem](../schemas/Column/ColumnItem.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
