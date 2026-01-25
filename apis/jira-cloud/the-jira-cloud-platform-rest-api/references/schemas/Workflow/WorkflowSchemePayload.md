# WorkflowSchemePayload

The payload for creating a workflow scheme. See https://www.atlassian.com/software/jira/guides/workflows/overview\#what-is-a-jira-workflow-scheme

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultWorkflow` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `description` | string | No | The description of the workflow scheme |
| `explicitMappings` | object | No | Association between issuetypes and workflows |
| `name` | string | No | The name of the workflow scheme |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |

