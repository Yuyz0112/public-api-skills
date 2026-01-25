# GET /workflows/integrations/{integration_id}/connections/{id}

**Resource:** [Workflow Integrations](../resources/Workflow-Integrations.md)
**Get Workflow Integration Connection**
**Operation ID:** `getWorkflowIntegrationConnection`

Get details about a Workflow Integration Connection.

Scoped OAuth requires: `workflow_integrations:connections.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The Workflow Integration Connection requested. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

**Success Response Schema:**

[WorkflowIntegrationConnection](../schemas/Workflow/WorkflowIntegrationConnection.md)

