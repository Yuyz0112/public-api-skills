# POST /workflows/integrations/{integration_id}/connections

**Resource:** [Workflow Integrations](../resources/Workflow-Integrations.md)
**Create Workflow Integration Connection**
**Operation ID:** `createWorkflowIntegrationConnection`

Create a new Workflow Integration Connection.

Scoped OAuth requires: `workflow_integrations:connections.write`


## Responses

| Status | Description |
|--------|-------------|
| 201 | The Workflow Integration Connection that was created. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

**Success Response Schema:**

[WorkflowIntegrationConnection](../schemas/Workflow/WorkflowIntegrationConnection.md)

