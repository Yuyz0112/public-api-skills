# PUT /rest/api/3/project/{projectId}/email

**Resource:** [Project email](../resources/Project-email.md)
**Set project's sender email**
**Operation ID:** `updateProjectEmail`

Sets the [project's sender email address](https://confluence.atlassian.com/x/dolKLg).

If `emailAddress` is an empty string, the default email address is restored.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) or *Administer Projects* [project permission.](https://confluence.atlassian.com/x/yodKLg)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectId` | path | integer (int64) | Yes | The project ID. |

## Request Body

The project's sender email address to be set.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ProjectEmailAddress](../schemas/Project/ProjectEmailAddress.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the project's sender email address is successfully set. |
| 400 | Returned if the request is not valid, if the email address is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to administer the project. |
| 404 | Returned if the project is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
