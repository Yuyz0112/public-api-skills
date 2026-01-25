# POST /incident_workflows/{id}/instances

**Resource:** [Incident Workflows](../resources/Incident-Workflows.md)
**Start an Incident Workflow Instance**
**Operation ID:** `createIncidentWorkflowInstance`

Start an Instance of an Incident Workflow. Sometimes referred to as "triggering a workflow on an incident."

An Incident Workflow is a sequence of configurable Steps and associated Triggers that can execute automated Actions for a given Incident.

Scoped OAuth requires: `incident_workflows:instances.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The Incident Workflow Instance |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

