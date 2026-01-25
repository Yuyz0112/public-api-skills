# GET /rest/api/3/component/{id}

**Resource:** [Project components](../resources/Project-components.md)
**Get component**
**Operation ID:** `getComponent`

Returns a component.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for project containing the component.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the component. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the component is not found or the user does not have permission to browse the project containing the component. |

**Success Response Schema:**

[ProjectComponent](../schemas/Project/ProjectComponent.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
