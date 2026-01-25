# PUT /rest/api/3/project/{projectIdOrKey}/features/{featureKey}

**Resource:** [Project features](../resources/Project-features.md)
**Set project feature state**
**Operation ID:** `toggleFeatureForProject`

Sets the state of a project feature.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The ID or (case-sensitive) key of the project. |
| `featureKey` | path | string | Yes | The key of the feature. |

## Request Body

Details of the feature state change.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ProjectFeatureState](../schemas/Project/ProjectFeatureState.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the project or project feature is not found. |

**Success Response Schema:**

[ContainerForProjectFeatures](../schemas/Container/ContainerForProjectFeatures.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
