# copilot-dotcom-pull-requests

Usage metrics for Copilot for pull requests.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `total_engaged_users` | integer | No | The number of users who used Copilot for Pull Requests on github.com to generate a pull request summary at least once. |
| `repositories` | object[] | No | Repositories in which users used Copilot for Pull Requests to generate pull request summaries |

## Nested Fields

### `repositories`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Repository name |
| `total_engaged_users` | integer | No | The number of users who generated pull request summaries using Copilot for Pull Requests in the given repository. |
| `models` | object[] | No | List of model metrics for custom models and the default model. |

#### `repositories.models`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Name of the model used for Copilot pull request summaries. If the default model is used will appear as 'default'. |
| `is_custom_model` | boolean | No | Indicates whether a model is custom or default. |
| `custom_model_training_date` | string | No | The training date for the custom model. |
| `total_pr_summaries_created` | integer | No | The number of pull request summaries generated using Copilot for Pull Requests in the given repository. |
| `total_engaged_users` | integer | No | The number of users who generated pull request summaries using Copilot for Pull Requests in the given repository and model. |

