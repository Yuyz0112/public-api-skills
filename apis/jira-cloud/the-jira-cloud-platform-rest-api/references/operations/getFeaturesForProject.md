# GET /rest/api/3/project/{projectIdOrKey}/features

**Resource:** [Project features](../resources/Project-features.md)
**Get project features**
**Operation ID:** `getFeaturesForProject`

Returns the list of features for a project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The ID or (case-sensitive) key of the project. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the project is not found. |

**Success Response Schema:**

[ContainerForProjectFeatures](../schemas/Container/ContainerForProjectFeatures.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
