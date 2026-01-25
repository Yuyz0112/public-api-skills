# GET /rest/api/3/user/columns

**Resource:** [Users](../resources/Users.md)
**Get user default columns**
**Operation ID:** `getUserDefaultColumns`

Returns the default [issue table columns](https://confluence.atlassian.com/x/XYdKLg) for the user. If `accountId` is not passed in the request, the calling user's details are returned.

**[Permissions](#permissions) required:**

 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLgl), to get the column details for any user.
 *  Permission to access Jira, to get the calling user's column details.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `accountId` | query | string | No | The account ID of the user, which uniquely identifies the user across all Atlassian products. For example, *5b10ac8d82e05b22cc7d4ef5*. |
| `username` | query | string | No | This parameter is no longer available See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission or is not accessing their user record. |
| 404 | Returned if the requested user is not found. |

**Success Response Schema:**

Array of [ColumnItem](../schemas/Column/ColumnItem.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
