# GET /workflows/integrations/{id}

**Resource:** [Workflow Integrations](../resources/Workflow-Integrations.md)
**Get Workflow Integration**
**Operation ID:** `getWorkflowIntegration`

Get details about a Workflow Integration.

Scoped OAuth requires: `workflow_integrations.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The Workflow Integration requested. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

**Success Response Schema:**

[WorkflowIntegration](../schemas/Workflow/WorkflowIntegration.md)

