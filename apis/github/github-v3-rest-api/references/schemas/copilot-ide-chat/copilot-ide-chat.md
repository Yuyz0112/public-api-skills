# copilot-ide-chat

Usage metrics for Copilot Chat in the IDE.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `total_engaged_users` | integer | No | Total number of users who prompted Copilot Chat in the IDE. |
| `editors` | object[] | No |  |

## Nested Fields

### `editors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Name of the given editor. |
| `total_engaged_users` | integer | No | The number of users who prompted Copilot Chat in the specified editor. |
| `models` | object[] | No | List of model metrics for custom models and the default model. |

#### `editors.models`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Name of the model used for Copilot Chat. If the default model is used will appear as 'default'. |
| `is_custom_model` | boolean | No | Indicates whether a model is custom or default. |
| `custom_model_training_date` | string | No | The training date for the custom model. |
| `total_engaged_users` | integer | No | The number of users who prompted Copilot Chat in the given editor and model. |
| `total_chats` | integer | No | The total number of chats initiated by users in the given editor and model. |
| `total_chat_insertion_events` | integer | No | The number of times users accepted a code suggestion from Copilot Chat using the 'Insert Code' UI element, for the given editor. |
| `total_chat_copy_events` | integer | No | The number of times users copied a code suggestion from Copilot Chat using the keyboard, or the 'Copy' UI element, for the given editor. |

