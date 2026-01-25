# issue-event

Issue Event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `actor` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `event` | string | Yes |  |
| `commit_id` | string | Yes |  |
| `commit_url` | string | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `issue` | [nullable-issue](nullable-issue.md) | No |  |
| `label` | [issue-event-label](issue-event-label.md) | No |  |
| `assignee` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `assigner` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `review_requester` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `requested_reviewer` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `requested_team` | [team](team.md) | No |  |
| `dismissed_review` | [issue-event-dismissed-review](issue-event-dismissed-review.md) | No |  |
| `milestone` | [issue-event-milestone](issue-event-milestone.md) | No |  |
| `project_card` | [issue-event-project-card](issue-event-project-card.md) | No |  |
| `rename` | [issue-event-rename](issue-event-rename.md) | No |  |
| `author_association` | [author-association](author-association.md) | No |  |
| `lock_reason` | string | No |  |
| `performed_via_github_app` | [nullable-integration](nullable-integration.md) | No |  |

