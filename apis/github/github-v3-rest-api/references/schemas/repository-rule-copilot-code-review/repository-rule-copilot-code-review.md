# repository-rule-copilot-code-review

Request Copilot code review for new pull requests automatically if the author has access to Copilot code review and their premium requests quota has not reached the limit.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: copilot_code_review | Yes |  |
| `parameters` | object | No |  |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `review_draft_pull_requests` | boolean | No | Copilot automatically reviews draft pull requests before they are marked as ready for review. |
| `review_on_push` | boolean | No | Copilot automatically reviews each new push to the pull request. |

