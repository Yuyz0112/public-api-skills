# DELETE /incident_workflows/{id}

**Resource:** [Incident Workflows](../resources/Incident-Workflows.md)
**Delete an Incident Workflow**
**Operation ID:** `deleteIncidentWorkflow`

Delete an existing Incident Workflow

An Incident Workflow is a sequence of configurable Steps and associated Triggers that can execute automated Actions for a given Incident.

Scoped OAuth requires: `incident_workflows.write`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The Incident Workflow was deleted successfully |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

