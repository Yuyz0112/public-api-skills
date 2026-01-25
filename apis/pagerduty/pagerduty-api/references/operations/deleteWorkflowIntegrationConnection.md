# DELETE /workflows/integrations/{integration_id}/connections/{id}

**Resource:** [Workflow Integrations](../resources/Workflow-Integrations.md)
**Delete Workflow Integration Connection**
**Operation ID:** `deleteWorkflowIntegrationConnection`

Delete a Workflow Integration Connection.

Scoped OAuth requires: `workflow_integrations:connections.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The Workflow Integration Connection was deleted successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

