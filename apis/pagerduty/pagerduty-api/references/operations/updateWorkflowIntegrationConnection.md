# PATCH /workflows/integrations/{integration_id}/connections/{id}

**Resource:** [Workflow Integrations](../resources/Workflow-Integrations.md)
**Update Workflow Integration Connection**
**Operation ID:** `updateWorkflowIntegrationConnection`

Update an existing Workflow Integration Connection.

Scoped OAuth requires: `workflow_integrations:connections.write`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The updated Workflow Integration Connection. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

**Success Response Schema:**

[WorkflowIntegrationConnection](../schemas/Workflow/WorkflowIntegrationConnection.md)

