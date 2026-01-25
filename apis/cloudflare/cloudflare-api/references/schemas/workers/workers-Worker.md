# workers_Worker

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_on` | string (date-time) | Yes | When the Worker was created. |
| `id` | string | Yes | Immutable ID of the Worker. |
| `logpush` | boolean | Yes | Whether logpush is enabled for the Worker. |
| `name` | string | Yes | Name of the Worker. |
| `observability` | object | Yes | Observability settings for the Worker. |
| `references` | object | Yes | Other resources that reference the Worker and depend on it existing. |
| `subdomain` | object | Yes | Subdomain settings for the Worker. |
| `tags` | string[] | Yes | Tags associated with the Worker. |
| `tail_consumers` | object[] | Yes | Other Workers that should consume logs from the Worker. |
| `updated_on` | string (date-time) | Yes | When the Worker was most recently updated. |

## Nested Fields

### `observability`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Whether observability is enabled for the Worker. |
| `head_sampling_rate` | number | No | The sampling rate for observability. From 0 to 1 (1 = 100%, 0.1 = 10%). |
| `logs` | object | No | Log settings for the Worker. |

#### `observability.logs`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Whether logs are enabled for the Worker. |
| `head_sampling_rate` | number | No | The sampling rate for logs. From 0 to 1 (1 = 100%, 0.1 = 10%). |
| `invocation_logs` | boolean | No | Whether [invocation logs](https://developers.cloudflare.com/workers/observability/logs/workers-logs/#invocation-logs) are enabled for the Worker. |

### `references`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dispatch_namespace_outbounds` | object[] | Yes | Other Workers that reference the Worker as an outbound for a dispatch namespace. |
| `domains` | object[] | Yes | Custom domains connected to the Worker. |
| `durable_objects` | object[] | Yes | Other Workers that reference Durable Object classes implemented by the Worker. |
| `queues` | object[] | Yes | Queues that send messages to the Worker. |
| `workers` | object[] | Yes | Other Workers that reference the Worker using [service bindings](https://developers.cloudflare.com/workers/runtime-apis/bindings/service-bindings/). |

#### `references.dispatch_namespace_outbounds`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `namespace_id` | string | Yes | ID of the dispatch namespace. |
| `namespace_name` | string | Yes | Name of the dispatch namespace. |
| `worker_id` | string | Yes | ID of the Worker using the dispatch namespace. |
| `worker_name` | string | Yes | Name of the Worker using the dispatch namespace. |

#### `references.domains`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `certificate_id` | string | Yes | ID of the TLS certificate issued for the custom domain. |
| `hostname` | string | Yes | Full hostname of the custom domain, including the zone name. |
| `id` | string | Yes | ID of the custom domain. |
| `zone_id` | string | Yes | ID of the zone. |
| `zone_name` | string | Yes | Name of the zone. |

#### `references.durable_objects`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `namespace_id` | string | Yes | ID of the Durable Object namespace being used. |
| `namespace_name` | string | Yes | Name of the Durable Object namespace being used. |
| `worker_id` | string | Yes | ID of the Worker using the Durable Object implementation. |
| `worker_name` | string | Yes | Name of the Worker using the Durable Object implementation. |

#### `references.queues`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `queue_consumer_id` | string | Yes | ID of the queue consumer configuration. |
| `queue_id` | string | Yes | ID of the queue. |
| `queue_name` | string | Yes | Name of the queue. |

#### `references.workers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | ID of the referencing Worker. |
| `name` | string | Yes | Name of the referencing Worker. |

### `subdomain`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Whether the *.workers.dev subdomain is enabled for the Worker. |
| `previews_enabled` | boolean | No | Whether [preview URLs](https://developers.cloudflare.com/workers/configuration/previews/) are enabled for the Worker. |

### `tail_consumers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Name of the consumer Worker. |

