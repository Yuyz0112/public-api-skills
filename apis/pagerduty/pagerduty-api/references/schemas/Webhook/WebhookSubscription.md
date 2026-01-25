# WebhookSubscription

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: webhook_subscription | Yes | The type indicating the schema of the object. |
| `active` | boolean | No | Determines whether this subscription will produce webhook events. |
| `delivery_method` | object | Yes |  |
| `description` | string | No | A short description of the webhook subscription. |
| `events` | string[] | Yes | The set of outbound event types the webhook will receive. |
| `filter` | object | Yes |  |
| `oauth_client` | object | No | OAuth client details. This field is populated in responses when oauth_client_id is set. |

## Nested Fields

### `delivery_method`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `secret` | string | No | The secret used to sign webhook payloads. Only provided on the initial create response. |
| `temporarily_disabled` | boolean | No | Whether or not this webhook subscription is temporarily disabled. Becomes `true` if the delivery method URL is repeatedly rejected by the server. |
| `type` | enum: http_delivery_method | Yes | Indicates the type of the delivery method. |
| `url` | string (url) | Yes | The destination URL for webhook delivery. |
| `custom_headers` | object[] | No | Optional headers to be set on this webhook subscription when sent. The header values are redacted in GET requests, but are not redacted on the webhook when delivered to the webhook's endpoint. |

#### `delivery_method.custom_headers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | The header name |
| `value` | string | No | The header value |

### `filter`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The id of the object being used as the filter.  This field is required for all filter types except account_reference. |
| `type` | enum: account_reference, service_reference, team_reference | Yes | The type of object being used as the filter. |

### `oauth_client`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The ID of the OAuth client |
| `type` | enum: oauth_client_reference | Yes | The type of object being referenced |
| `summary` | string | No | A short-form, server-generated string that provides succinct, important information about an object suitable for primary labeling of an entity in a client |

