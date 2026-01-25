# WorkflowElementReference

A reference to the location of the error. This will be null if the error does not refer to a specific element.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `propertyKey` | string | No | A property key. |
| `ruleId` | string | No | A rule ID. |
| `statusMappingReference` | [ProjectAndIssueTypePair](ProjectAndIssueTypePair.md) | No |  |
| `statusReference` | string | No | A status reference. |
| `transitionId` | string | No | A transition ID. |

