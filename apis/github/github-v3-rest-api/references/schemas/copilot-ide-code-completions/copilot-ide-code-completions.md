# copilot-ide-code-completions

Usage metrics for Copilot editor code completions in the IDE.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `total_engaged_users` | integer | No | Number of users who accepted at least one Copilot code suggestion, across all active editors. Includes both full and partial acceptances. |
| `languages` | object[] | No | Code completion metrics for active languages. |
| `editors` | object[] | No |  |

## Nested Fields

### `languages`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Name of the language used for Copilot code completion suggestions. |
| `total_engaged_users` | integer | No | Number of users who accepted at least one Copilot code completion suggestion for the given language. Includes both full and partial acceptances. |

### `editors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Name of the given editor. |
| `total_engaged_users` | integer | No | Number of users who accepted at least one Copilot code completion suggestion for the given editor. Includes both full and partial acceptances. |
| `models` | object[] | No | List of model metrics for custom models and the default model. |

#### `editors.models`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Name of the model used for Copilot code completion suggestions. If the default model is used will appear as 'default'. |
| `is_custom_model` | boolean | No | Indicates whether a model is custom or default. |
| `custom_model_training_date` | string | No | The training date for the custom model. |
| `total_engaged_users` | integer | No | Number of users who accepted at least one Copilot code completion suggestion for the given editor, for the given language and model. Includes both full and partial acceptances. |
| `languages` | object[] | No | Code completion metrics for active languages, for the given editor. |

