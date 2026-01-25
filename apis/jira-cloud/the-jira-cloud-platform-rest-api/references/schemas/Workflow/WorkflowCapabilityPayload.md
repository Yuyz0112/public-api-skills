# WorkflowCapabilityPayload

The payload for creating a workflows. See https://www.atlassian.com/software/jira/guides/workflows/overview\#what-is-a-jira-workflow

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `statuses` | StatusPayload[] | No | The statuses for the workflow |
| `workflowScheme` | [WorkflowSchemePayload](WorkflowSchemePayload.md) | No |  |
| `workflows` | WorkflowPayload[] | No | The transitions for the workflow |

