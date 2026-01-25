# pages_deployment_config_values

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ai_bindings` | object | No | Constellation bindings used for Pages Functions. |
| `always_use_latest_compatibility_date` | boolean | Yes | Whether to always use the latest compatibility date for Pages Functions. |
| `analytics_engine_datasets` | object | No | Analytics Engine bindings used for Pages Functions. |
| `browsers` | object | No | Browser bindings used for Pages Functions. |
| `build_image_major_version` | integer | Yes | The major version of the build image to use for Pages Functions. |
| `compatibility_date` | string | Yes | Compatibility date used for Pages Functions. |
| `compatibility_flags` | string[] | Yes | Compatibility flags used for Pages Functions. |
| `d1_databases` | object | No | D1 databases used for Pages Functions. |
| `durable_object_namespaces` | object | No | Durable Object namespaces used for Pages Functions. |
| `env_vars` | [pages_env_vars](pages-env-vars.md) | Yes |  |
| `fail_open` | boolean | Yes | Whether to fail open when the deployment config cannot be applied. |
| `hyperdrive_bindings` | object | No | Hyperdrive bindings used for Pages Functions. |
| `kv_namespaces` | object | No | KV namespaces used for Pages Functions. |
| `limits` | object | No | Limits for Pages Functions. |
| `mtls_certificates` | object | No | mTLS bindings used for Pages Functions. |
| `placement` | object | No | Placement setting used for Pages Functions. |
| `queue_producers` | object | No | Queue Producer bindings used for Pages Functions. |
| `r2_buckets` | object | No | R2 buckets used for Pages Functions. |
| `services` | object | No | Services used for Pages Functions. |
| `usage_model` | enum: standard, bundled, unbound | Yes | The usage model for Pages Functions. |
| `vectorize_bindings` | object | No | Vectorize bindings used for Pages Functions. |
| `wrangler_config_hash` | string | No | Hash of the Wrangler configuration used for the deployment. |

## Nested Fields

### `limits`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cpu_ms` | integer | Yes | CPU time limit in milliseconds. |

### `placement`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `mode` | string | Yes | Placement mode. |

