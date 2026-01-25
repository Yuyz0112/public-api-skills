# PUT /rest/api/3/settings/columns

**Resource:** [Issue navigator settings](../resources/Issue-navigator-settings.md)
**Set issue navigator default columns**
**Operation ID:** `setIssueNavigatorDefaultColumns`

Sets the default issue navigator columns.

The `columns` parameter accepts a navigable field value and is expressed as HTML form data. To specify multiple columns, pass multiple `columns` parameters. For example, in curl:

`curl -X PUT -d columns=summary -d columns=description https://your-domain.atlassian.net/rest/api/3/settings/columns`

If no column details are sent, then all default columns are removed.

A navigable field is one that can be used as a column on the issue navigator. Find details of navigable issue columns using [Get fields](#api-rest-api-3-field-get).

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

A navigable field value.

**Required:** Yes

**Content Types:** `*/*`, `multipart/form-data`

**Schema:** [ColumnRequestBody](../schemas/Column/ColumnRequestBody.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if invalid parameters are passed. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if a navigable field value is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
