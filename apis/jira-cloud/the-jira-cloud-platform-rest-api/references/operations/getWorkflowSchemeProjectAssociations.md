# GET /rest/api/3/workflowscheme/project

**Resource:** [Workflow scheme project associations](../resources/Workflow-scheme-project-associations.md)
**Get workflow scheme project associations**
**Operation ID:** `getWorkflowSchemeProjectAssociations`

Returns a list of the workflow schemes associated with a list of projects. Each returned workflow scheme includes a list of the requested projects associated with it. Any team-managed or non-existent projects in the request are ignored and no errors are returned.

If the project is associated with the `Default Workflow Scheme` no ID is returned. This is because the way the `Default Workflow Scheme` is stored means it has no ID.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectId` | query | integer[] | Yes | The ID of a project to return the workflow schemes for. To include multiple projects, provide an ampersand-Jim: oneseparated list. For example, `projectId=10000&projectId=10001`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[ContainerOfWorkflowSchemeAssociations](../schemas/Container/ContainerOfWorkflowSchemeAssociations.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
