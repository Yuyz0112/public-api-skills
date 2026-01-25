# GET /workflows/integrations/{integration_id}/connections

**Resource:** [Workflow Integrations](../resources/Workflow-Integrations.md)
**List Workflow Integration Connections**
**Operation ID:** `listWorkflowIntegrationConnectionsByIntegration`

List all Workflow Integration Connections for a specific Workflow Integration.

Scoped OAuth requires: `workflow_integrations:connections.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated list of Workflow Integration Connections. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

