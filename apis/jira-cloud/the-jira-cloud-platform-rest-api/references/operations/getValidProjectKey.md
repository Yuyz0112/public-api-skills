# GET /rest/api/3/projectvalidate/validProjectKey

**Resource:** [Project key and name validation](../resources/Project-key-and-name-validation.md)
**Get valid project key**
**Operation ID:** `getValidProjectKey`

Validates a project key and, if the key is invalid or in use, generates a valid random string for the project key.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | query | string | No | The project key. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect. |

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
