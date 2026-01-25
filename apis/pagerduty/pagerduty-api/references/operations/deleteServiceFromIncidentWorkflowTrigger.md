# DELETE /incident_workflows/triggers/{trigger_id}/services/{service_id}

**Resource:** [Incident Workflows](../resources/Incident-Workflows.md)
**Dissociate a Trigger and Service**
**Operation ID:** `deleteServiceFromIncidentWorkflowTrigger`

Remove a an existing Service from an Incident Workflow Trigger

Scoped OAuth requires: `incident_workflows.write`


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

