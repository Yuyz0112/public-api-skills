# GET /rest/api/3/project/type/accessible

**Resource:** [Project types](../resources/Project-types.md)
**Get licensed project types**
**Operation ID:** `getAllAccessibleProjectTypes`

Returns all [project types](https://confluence.atlassian.com/x/Var1Nw) with a valid license.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |

**Success Response Schema:**

Array of [ProjectType](../schemas/Project/ProjectType.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
