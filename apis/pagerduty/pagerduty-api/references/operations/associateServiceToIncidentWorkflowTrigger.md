# POST /incident_workflows/triggers/{id}/services

**Resource:** [Incident Workflows](../resources/Incident-Workflows.md)
**Associate a Trigger and Service**
**Operation ID:** `associateServiceToIncidentWorkflowTrigger`

Associate a Service with an existing Incident Workflow Trigger

Scoped OAuth requires: `incident_workflows.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The updated Incident Workflow Trigger |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

