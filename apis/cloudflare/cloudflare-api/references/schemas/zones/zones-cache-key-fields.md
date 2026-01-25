# zones_cache_key_fields

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | enum: cache_key_fields | No | Control specifically what variables to include when deciding which
resources to cache. This allows customers to determine what to cache
based on something other than just the URL.
 |
| `value` | object | No |  |

## Nested Fields

### `value`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cookie` | object | No | Controls which cookies appear in the Cache Key.
 |
| `header` | object | No | Controls which headers go into the Cache Key. Exactly one of
`include` or `exclude` is expected.
 |
| `host` | object | No | Determines which host header to include in the Cache Key.
 |
| `query_string` | object | No | Controls which URL query string parameters go into the Cache
Key. Exactly one of `include` or `exclude` is expected.
 |
| `user` | object | No | Feature fields to add features about the end-user (client) into
the Cache Key.
 |

#### `value.cookie`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `check_presence` | string[] | No | A list of cookies to check for the presence of, without
including their actual values.
 |
| `include` | string[] | No | A list of cookies to include.
 |

#### `value.header`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `check_presence` | string[] | No | A list of headers to check for the presence of, without
including their actual values.
 |
| `exclude` | string[] | No | A list of headers to ignore.
 |
| `include` | string[] | No | A list of headers to include.
 |

#### `value.host`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `resolved` | boolean | No | Whether to include the Host header in the HTTP request sent
to the origin.
 |

#### `value.query_string`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `exclude` | any | No |  |
| `include` | any | No |  |

#### `value.user`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `device_type` | boolean | No | Classifies a request as `mobile`, `desktop`, or `tablet`
based on the User Agent.
 |
| `geo` | boolean | No | Includes the client's country, derived from the IP address.
 |
| `lang` | boolean | No | Includes the first language code contained in the
`Accept-Language` header sent by the client.
 |

