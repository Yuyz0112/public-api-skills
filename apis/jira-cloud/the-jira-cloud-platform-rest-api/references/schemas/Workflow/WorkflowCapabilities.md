# WorkflowCapabilities

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `connectRules` | AvailableWorkflowConnectRule[] | No | The Connect provided ecosystem rules available. |
| `editorScope` | enum: PROJECT, GLOBAL | No | The scope of the workflow capabilities. `GLOBAL` for company-managed projects and `PROJECT` for team-managed projects. |
| `forgeRules` | AvailableWorkflowForgeRule[] | No | The Forge provided ecosystem rules available. |
| `projectTypes` | string[] | No | The types of projects that this capability set is available for. |
| `systemRules` | AvailableWorkflowSystemRule[] | No | The Atlassian provided system rules available. |
| `triggerRules` | AvailableWorkflowTriggers[] | No | The trigger rules available. |

