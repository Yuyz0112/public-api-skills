# GET /rest/api/3/user/bulk/migration

**Resource:** [Users](../resources/Users.md)
**Get account IDs for users**
**Operation ID:** `bulkGetUsersMigration`

Returns the account IDs for the users specified in the `key` or `username` parameters. Note that multiple `key` or `username` parameters can be specified.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `username` | query | string[] | No | Username of a user. To specify multiple users, pass multiple copies of this parameter. For example, `username=fred&username=barney`. Required if `key` isn't provided. Cannot be provided if `key` is present. |
| `key` | query | string[] | No | Key of a user. To specify multiple users, pass multiple copies of this parameter. For example, `key=fred&key=barney`. Required if `username` isn't provided. Cannot be provided if `username` is present. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if `key` or `username` |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

Array of [UserMigrationBean](../schemas/User/UserMigrationBean.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
