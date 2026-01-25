# ActivityLog

An event returned by the Activity Logs API.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The ID of the event. |
| `timestamp` | number | Yes | The timestamp of the event in seconds since the Unix epoch. |
| `actor` | object,null | Yes | The user who performed the action. |
| `action` | object | Yes | The task or activity the actor performed. |
| `entity` | any | Yes | The resource the actor took the action on. It can be a user, file, project or other resource types. |
| `context` | object | Yes | Contextual information about the event. |

## Nested Fields

### `action`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | Yes | The type of the action. |
| `details` | object,null | Yes | Metadata of the action. Each action type supports its own metadata attributes. |

### `context`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `client_name` | string,null | Yes | The third-party application that triggered the event, if applicable. |
| `ip_address` | string | Yes | The IP address from of the client that sent the event request. |
| `is_figma_support_team_action` | boolean | Yes | If Figma's Support team triggered the event. This is either true or false. |
| `org_id` | string | Yes | The id of the organization where the event took place. |
| `team_id` | string,null | Yes | The id of the team where the event took place -- if this took place in a specific team. |

