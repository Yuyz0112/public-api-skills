# IncidentWorkflowInstance

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: incident_workflow_instance | No | A string that determines the schema of the object. This must be the standard name for the entity, suffixed by `_reference` if the object is a reference. |
| `incident` | [Reference](Reference.md) | No |  |

