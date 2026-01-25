# GET /rest/api/3/application-properties/advanced-settings

**Resource:** [Jira settings](../resources/Jira-settings.md)
**Get advanced settings**
**Operation ID:** `getAdvancedSettings`

Returns the application properties that are accessible on the *Advanced Settings* page. To navigate to the *Advanced Settings* page in Jira, choose the Jira icon > **Jira settings** > **System**, **General Configuration** and then click **Advanced Settings** (in the upper right).

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user is not an administrator. |

**Success Response Schema:**

Array of [ApplicationProperty](../schemas/Application/ApplicationProperty.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
