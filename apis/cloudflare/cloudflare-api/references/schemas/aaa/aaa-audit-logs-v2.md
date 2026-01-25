# aaa_audit-logs-v2

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | object | No | Contains account related information. |
| `action` | object | No | Provides information about the action performed. |
| `actor` | object | No | Provides details about the actor who performed the action. |
| `id` | [aaa_schemas-identifier](aaa-schemas-identifier.md) | No |  |
| `raw` | object | No | Provides raw information about the request and response. |
| `resource` | object | No | Provides details about the affected resource. |
| `zone` | object | No | Provides details about the zone affected by the action. |

## Nested Fields

### `account`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | A unique identifier for the account. |
| `name` | string | No | A string that identifies the account name. |

### `action`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | A short description of the action performed. |
| `result` | string | No | The result of the action, indicating success or failure. |
| `time` | string (date-time) | No | A timestamp indicating when the action was logged. |
| `type` | string | No | A short string that describes the action that was performed. |

### `actor`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `context` | enum: api_key, api_token, dash... | No |  |
| `email` | string (email) | No | The email of the actor who performed the action. |
| `id` | string | No | The ID of the actor who performed the action. If a user performed the action, this will be their User ID. |
| `ip_address` | string (ipv4 | ipv6) | No | The IP address of the request that performed the action. |
| `token_id` | string | No | Filters by the API token ID when the actor context is an api_token. |
| `token_name` | string | No | Filters by the API token name when the actor context is an api_token. |
| `type` | enum: account, cloudflare_admin, system... | No | The type of actor. |

### `raw`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cf_ray_id` | string | No | The Cloudflare Ray ID for the request. |
| `method` | string | No | The HTTP method of the request. |
| `status_code` | integer | No | The HTTP response status code returned by the API. |
| `uri` | string | No | The URI of the request. |
| `user_agent` | string | No | The client's user agent string sent with the request. |

### `resource`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The unique identifier for the affected resource. |
| `product` | string | No | The Cloudflare product associated with the resource. |
| `request` | object | No |  |
| `response` | object | No |  |
| `scope` | object | No | The scope of the resource. |
| `type` | string | No | The type of the resource. |

### `zone`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | A string that identifies the zone id. |
| `name` | string | No | A string that identifies the zone name. |

