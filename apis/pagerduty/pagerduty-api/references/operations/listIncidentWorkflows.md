# GET /incident_workflows

**Resource:** [Incident Workflows](../resources/Incident-Workflows.md)
**List Incident Workflows**
**Operation ID:** `listIncidentWorkflows`

List existing Incident Workflows.

This is the best method to use to list all Incident Workflows in your account. If your use case requires listing Incident Workflows associated with a particular Service, you can use the "List Triggers" method to find Incident Workflows configured to start for Incidents in a given Service.

An Incident Workflow is a sequence of configurable Steps and associated Triggers that can execute automated Actions for a given Incident.

Scoped OAuth requires: `incident_workflows.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of Incident Workflows. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

