# GET /rest/api/3/component/{id}/relatedIssueCounts

**Resource:** [Project components](../resources/Project-components.md)
**Get component issues count**
**Operation ID:** `getComponentRelatedIssues`

Returns the counts of issues assigned to the component.

This operation can be accessed anonymously.

**Deprecation notice:** The required OAuth 2.0 scopes will be updated on June 15, 2024.

 *  **Classic**: `read:jira-work`
 *  **Granular**: `read:field:jira`, `read:project.component:jira`

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the component. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the component is not found. |

**Success Response Schema:**

[ComponentIssuesCount](../schemas/Component/ComponentIssuesCount.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
