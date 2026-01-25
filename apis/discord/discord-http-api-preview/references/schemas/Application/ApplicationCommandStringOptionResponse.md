# ApplicationCommandStringOptionResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: 3 | Yes |  |
| `name` | string | Yes |  |
| `name_localized` | string | No |  |
| `name_localizations` | object,null | No |  |
| `description` | string | Yes |  |
| `description_localized` | string | No |  |
| `description_localizations` | object,null | No |  |
| `required` | boolean | No |  |
| `autocomplete` | boolean | No |  |
| `choices` | ApplicationCommandOptionStringChoiceResponse[] | No |  |
| `min_length` | integer (int32) | No |  |
| `max_length` | integer (int32) | No |  |

