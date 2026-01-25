# PUT /rest/api/3/mypreferences/locale

**Resource:** [Myself](../resources/Myself.md)
**Set locale**
**Operation ID:** `setLocale`
⚠️ **Deprecated**

Deprecated, use [ Update a user profile](https://developer.atlassian.com/cloud/admin/user-management/rest/#api-users-account-id-manage-profile-patch) from the user management REST API instead.

Sets the locale of the user. The locale must be one supported by the instance of Jira.

**[Permissions](#permissions) required:** Permission to access Jira.

## Request Body

The locale defined in a LocaleBean.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [Locale](../schemas/Locale/Locale.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

## Security

- **basicAuth**
