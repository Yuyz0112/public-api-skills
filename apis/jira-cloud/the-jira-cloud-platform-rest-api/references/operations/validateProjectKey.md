# GET /rest/api/3/projectvalidate/key

**Resource:** [Project key and name validation](../resources/Project-key-and-name-validation.md)
**Validate project key**
**Operation ID:** `validateProjectKey`

Validates a project key by confirming the key is a valid string and not in use.

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

**Success Response Schema:**

[ErrorCollection](../schemas/Error/ErrorCollection.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
