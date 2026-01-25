# PUT /rest/api/3/priority/default

**Resource:** [Issue priorities](../resources/Issue-priorities.md)
**Set default priority**
**Operation ID:** `setDefaultPriority`

Sets default issue priority.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SetDefaultPriorityRequest](../schemas/Set/SetDefaultPriorityRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 404 | Returned if the issue priority isn't found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
