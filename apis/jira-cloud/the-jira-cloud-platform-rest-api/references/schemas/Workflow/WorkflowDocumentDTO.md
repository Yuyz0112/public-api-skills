# WorkflowDocumentDTO

The workflow stored for the specified version.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | string | No |  |
| `description` | string | No |  |
| `id` | string | No |  |
| `lastUpdateAuthorAAID` | string | No |  |
| `loopedTransitionContainerLayout` | [WorkflowLayout](WorkflowLayout.md) | No |  |
| `name` | string | No |  |
| `scope` | [WorkflowScope](WorkflowScope.md) | No |  |
| `startPointLayout` | [WorkflowLayout](WorkflowLayout.md) | No |  |
| `statuses` | WorkflowReferenceStatus[] | No |  |
| `transitions` | WorkflowTransitions[] | No |  |
| `updated` | string | No |  |
| `version` | [DocumentVersion](DocumentVersion.md) | No |  |

