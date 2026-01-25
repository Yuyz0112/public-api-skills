# IssueLayoutPayload

Defines the payload to configure the issue layouts for a project.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `containerId` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `issueLayoutType` | enum: ISSUE_VIEW, ISSUE_CREATE, REQUEST_FORM | No | The issue layout type |
| `items` | IssueLayoutItemPayload[] | No | The configuration of items in the issue layout |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |

