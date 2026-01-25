# GET /incident_workflows/{id}

**Resource:** [Incident Workflows](../resources/Incident-Workflows.md)
**Get an Incident Workflow**
**Operation ID:** `getIncidentWorkflow`

Get an existing Incident Workflow

An Incident Workflow is a sequence of configurable Steps and associated Triggers that can execute automated Actions for a given Incident.

Scoped OAuth requires: `incident_workflows.read`


## Responses

| Status | Description |
|--------|-------------|
| 201 | The Incident Workflow |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

