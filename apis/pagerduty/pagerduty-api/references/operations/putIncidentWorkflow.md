# PUT /incident_workflows/{id}

**Resource:** [Incident Workflows](../resources/Incident-Workflows.md)
**Update an Incident Workflow**
**Operation ID:** `putIncidentWorkflow`

Update an Incident Workflow

An Incident Workflow is a sequence of configurable Steps and associated Triggers that can execute automated Actions for a given Incident.

Scoped OAuth requires: `incident_workflows.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The changed Incident Workflow |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

