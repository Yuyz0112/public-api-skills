# EventRuleActionsCommon

When an event matches this Event Rule, the actions that will be taken to change the resulting Alert and Incident.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `annotate` | object | No | Set a note on the resulting incident. |
| `event_action` | object | No | Set whether the resulting alert status is trigger or resolve. |
| `extractions` | any[] | No | Dynamically extract values to set and modify new and existing PD-CEF fields. |
| `priority` | object | No | Set the priority ID for the resulting incident. You can find the priority you want by calling the priorities endpoint. |
| `severity` | object | No | Set the severity of the resulting alert. |
| `suppress` | object | No | Set whether the resulting alert is suppressed. Can optionally be used with a threshold where resulting alerts will be suppressed until the threshold is met in a window of time. If using a threshold the rule must also set a route action. |
| `suspend` | object | No | Set the length of time to suspend the resulting alert before triggering. Rules with a suspend action must also set a route action, and cannot have a suppress with threshold action |

## Nested Fields

### `annotate`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | string | Yes | The content of the note. |

### `event_action`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | enum: trigger, resolve | Yes |  |

### `priority`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | string | Yes | The priority ID. |

### `severity`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | enum: info, warning, error... | Yes |  |

### `suppress`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | boolean | Yes |  |
| `threshold_value` | integer | No | The number of occurences needed during the window of time to trigger the theshold. |
| `threshold_time_unit` | enum: seconds, minutes, hours | No | The time unit for the window of time. |
| `threshold_time_amount` | integer | No | The amount of time units for the window of time. |

### `suspend`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `value` | integer | Yes | The amount of time to suspend the alert in seconds. |

