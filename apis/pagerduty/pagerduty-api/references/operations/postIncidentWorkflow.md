# POST /incident_workflows

**Resource:** [Incident Workflows](../resources/Incident-Workflows.md)
**Create an Incident Workflow**
**Operation ID:** `postIncidentWorkflow`

Create a new Incident Workflow

An Incident Workflow is a sequence of configurable Steps and associated Triggers that can execute automated Actions for a given Incident.

Scoped OAuth requires: `incident_workflows.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The new Incident Workflow |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

