# ApplicationCommandIntegerOptionResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: 4 | Yes |  |
| `name` | string | Yes |  |
| `name_localized` | string | No |  |
| `name_localizations` | object,null | No |  |
| `description` | string | Yes |  |
| `description_localized` | string | No |  |
| `description_localizations` | object,null | No |  |
| `required` | boolean | No |  |
| `autocomplete` | boolean | No |  |
| `choices` | ApplicationCommandOptionIntegerChoiceResponse[] | No |  |
| `min_value` | [Int53Type](Int53Type.md) | No |  |
| `max_value` | [Int53Type](Int53Type.md) | No |  |

