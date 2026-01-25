# GET /rest/api/3/project/type/{projectTypeKey}

**Resource:** [Project types](../resources/Project-types.md)
**Get project type by key**
**Operation ID:** `getProjectTypeByKey`

Returns a [project type](https://confluence.atlassian.com/x/Var1Nw).

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectTypeKey` | path | enum: software, service_desk, business... | Yes | The key of the project type. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect. |
| 404 | Returned if the project type is not found. |

**Success Response Schema:**

[ProjectType](../schemas/Project/ProjectType.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
