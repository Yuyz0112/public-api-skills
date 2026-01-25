# Workflow Integrations

Workflow Integrations are a way to connect PagerDuty to other tools and services.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/workflows/integrations` | List Workflow Integrations | [View](../operations/listWorkflowIntegrations.md) |
| GET | `/workflows/integrations/{id}` | Get Workflow Integration | [View](../operations/getWorkflowIntegration.md) |
| GET | `/workflows/integrations/connections` | List all Workflow Integration Connections | [View](../operations/listWorkflowIntegrationConnections.md) |
| GET | `/workflows/integrations/{integration_id}/connections` | List Workflow Integration Connections | [View](../operations/listWorkflowIntegrationConnectionsByIntegration.md) |
| POST | `/workflows/integrations/{integration_id}/connections` | Create Workflow Integration Connection | [View](../operations/createWorkflowIntegrationConnection.md) |
| GET | `/workflows/integrations/{integration_id}/connections/{id}` | Get Workflow Integration Connection | [View](../operations/getWorkflowIntegrationConnection.md) |
| DELETE | `/workflows/integrations/{integration_id}/connections/{id}` | Delete Workflow Integration Connection | [View](../operations/deleteWorkflowIntegrationConnection.md) |
| PATCH | `/workflows/integrations/{integration_id}/connections/{id}` | Update Workflow Integration Connection | [View](../operations/updateWorkflowIntegrationConnection.md) |
