# review-custom-gates-state-required

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `environment_name` | string | Yes | The name of the environment to approve or reject. |
| `state` | enum: approved, rejected | Yes | Whether to approve or reject deployment to the specified environments. |
| `comment` | string | No | Optional comment to include with the review. |

