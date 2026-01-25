# Incident Workflows

An Incident Workflow is a sequence of configurable Steps and associated Triggers that can execute automated Actions for a given Incident.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/incident_workflows` | List Incident Workflows | [View](../operations/listIncidentWorkflows.md) |
| POST | `/incident_workflows` | Create an Incident Workflow | [View](../operations/postIncidentWorkflow.md) |
| GET | `/incident_workflows/{id}` | Get an Incident Workflow | [View](../operations/getIncidentWorkflow.md) |
| PUT | `/incident_workflows/{id}` | Update an Incident Workflow | [View](../operations/putIncidentWorkflow.md) |
| DELETE | `/incident_workflows/{id}` | Delete an Incident Workflow | [View](../operations/deleteIncidentWorkflow.md) |
| POST | `/incident_workflows/{id}/instances` | Start an Incident Workflow Instance | [View](../operations/createIncidentWorkflowInstance.md) |
| GET | `/incident_workflows/actions` | List Actions | [View](../operations/listIncidentWorkflowActions.md) |
| GET | `/incident_workflows/actions/{id}` | Get an Action | [View](../operations/getIncidentWorkflowAction.md) |
| GET | `/incident_workflows/triggers` | List Triggers | [View](../operations/listIncidentWorkflowTriggers.md) |
| POST | `/incident_workflows/triggers` | Create a Trigger | [View](../operations/createIncidentWorkflowTrigger.md) |
| GET | `/incident_workflows/triggers/{id}` | Get a Trigger | [View](../operations/getIncidentWorkflowTrigger.md) |
| PUT | `/incident_workflows/triggers/{id}` | Update a Trigger | [View](../operations/updateIncidentWorkflowTrigger.md) |
| DELETE | `/incident_workflows/triggers/{id}` | Delete a Trigger | [View](../operations/deleteIncidentWorkflowTrigger.md) |
| POST | `/incident_workflows/triggers/{id}/services` | Associate a Trigger and Service | [View](../operations/associateServiceToIncidentWorkflowTrigger.md) |
| DELETE | `/incident_workflows/triggers/{trigger_id}/services/{service_id}` | Dissociate a Trigger and Service | [View](../operations/deleteServiceFromIncidentWorkflowTrigger.md) |
