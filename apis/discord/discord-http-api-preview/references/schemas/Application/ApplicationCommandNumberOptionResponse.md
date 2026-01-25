# ApplicationCommandNumberOptionResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: 10 | Yes |  |
| `name` | string | Yes |  |
| `name_localized` | string | No |  |
| `name_localizations` | object,null | No |  |
| `description` | string | Yes |  |
| `description_localized` | string | No |  |
| `description_localizations` | object,null | No |  |
| `required` | boolean | No |  |
| `autocomplete` | boolean | No |  |
| `choices` | ApplicationCommandOptionNumberChoiceResponse[] | No |  |
| `min_value` | number (double) | No |  |
| `max_value` | number (double) | No |  |

