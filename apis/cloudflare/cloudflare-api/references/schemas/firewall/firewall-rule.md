# firewall_rule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allowed_modes` | firewall_schemas-mode[] | Yes | The available actions that a rule can apply to a matched request. |
| `configuration` | [firewall_configuration](firewall-configuration.md) | Yes |  |
| `created_on` | string (date-time) | No | The timestamp of when the rule was created. |
| `id` | [firewall_schemas-identifier](firewall-schemas-identifier.md) | Yes |  |
| `mode` | [firewall_schemas-mode](firewall-schemas-mode.md) | Yes |  |
| `modified_on` | string (date-time) | No | The timestamp of when the rule was last modified. |
| `notes` | [firewall_notes](firewall-notes.md) | No |  |

