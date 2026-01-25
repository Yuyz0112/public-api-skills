# GET /rest/api/3/workflows/defaultEditor

**Resource:** [Workflows](../resources/Workflows.md)
**Get the user's default workflow editor**
**Operation ID:** `getDefaultEditor`

Get the user's default workflow editor. This can be either the new editor or the legacy editor.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |

**Success Response Schema:**

[DefaultWorkflowEditorResponse](../schemas/Default/DefaultWorkflowEditorResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
