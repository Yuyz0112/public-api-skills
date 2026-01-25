# copilot-dotcom-chat

Usage metrics for Copilot Chat in GitHub.com

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `total_engaged_users` | integer | No | Total number of users who prompted Copilot Chat on github.com at least once. |
| `models` | object[] | No | List of model metrics for a custom models and the default model. |

## Nested Fields

### `models`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Name of the model used for Copilot Chat. If the default model is used will appear as 'default'. |
| `is_custom_model` | boolean | No | Indicates whether a model is custom or default. |
| `custom_model_training_date` | string | No | The training date for the custom model (if applicable). |
| `total_engaged_users` | integer | No | Total number of users who prompted Copilot Chat on github.com at least once for each model. |
| `total_chats` | integer | No | Total number of chats initiated by users on github.com. |

