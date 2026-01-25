# repository-ruleset

A set of rules to apply when specified conditions are met.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The ID of the ruleset |
| `name` | string | Yes | The name of the ruleset |
| `target` | enum: branch, tag, push... | No | The target of the ruleset |
| `source_type` | enum: Repository, Organization, Enterprise | No | The type of the source of the ruleset |
| `source` | string | Yes | The name of the source |
| `enforcement` | [repository-rule-enforcement](repository-rule-enforcement.md) | Yes |  |
| `bypass_actors` | repository-ruleset-bypass-actor[] | No | The actors that can bypass the rules in this ruleset |
| `current_user_can_bypass` | enum: always, pull_requests_only, never... | No | The bypass type of the user making the API request for this ruleset. This field is only returned when
querying the repository-level endpoint. |
| `node_id` | string | No |  |
| `_links` | object | No |  |
| `conditions` | any | No |  |
| `rules` | repository-rule[] | No |  |
| `created_at` | string (date-time) | No |  |
| `updated_at` | string (date-time) | No |  |

## Nested Fields

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `self` | object | No |  |
| `html` | object | No |  |

#### `_links.self`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string | No | The URL of the ruleset |

#### `_links.html`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string | No | The html URL of the ruleset |

