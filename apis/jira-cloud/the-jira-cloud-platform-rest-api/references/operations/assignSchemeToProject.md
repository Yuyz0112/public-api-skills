# PUT /rest/api/3/workflowscheme/project

**Resource:** [Workflow scheme project associations](../resources/Workflow-scheme-project-associations.md)
**Assign workflow scheme to project**
**Operation ID:** `assignSchemeToProject`

Assigns a workflow scheme to a project. This operation is performed only when there are no issues in the project.

Workflow schemes can only be assigned to classic projects.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowSchemeProjectAssociation](../schemas/Workflow/WorkflowSchemeProjectAssociation.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the workflow scheme or the project are not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
