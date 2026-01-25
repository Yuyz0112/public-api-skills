# webhook-discussion-unanswered

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: unanswered | Yes |  |
| `discussion` | [discussion](discussion.md) | Yes |  |
| `old_answer` | [webhooks_answer](webhooks-answer.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | No |  |

