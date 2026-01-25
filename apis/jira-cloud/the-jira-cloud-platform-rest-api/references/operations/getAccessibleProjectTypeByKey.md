# GET /rest/api/3/project/type/{projectTypeKey}/accessible

**Resource:** [Project types](../resources/Project-types.md)
**Get accessible project type by key**
**Operation ID:** `getAccessibleProjectTypeByKey`

Returns a [project type](https://confluence.atlassian.com/x/Var1Nw) if it is accessible to the user.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectTypeKey` | path | enum: software, service_desk, business... | Yes | The key of the project type. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project type is not accessible to the user. |

**Success Response Schema:**

[ProjectType](../schemas/Project/ProjectType.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
