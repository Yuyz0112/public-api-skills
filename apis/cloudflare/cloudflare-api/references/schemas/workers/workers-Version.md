# workers_Version

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `annotations` | object | No | Metadata about the version. |
| `assets` | object | No | Configuration for assets within a Worker.

[`_headers`](https://developers.cloudflare.com/workers/static-assets/headers/#custom-headers) and
[`_redirects`](https://developers.cloudflare.com/workers/static-assets/redirects/) files should be
included as modules named `_headers` and `_redirects` with content type `text/plain`.
 |
| `bindings` | [workers_bindings](workers-bindings.md) | No |  |
| `compatibility_date` | [workers_compatibility_date](workers-compatibility-date.md) | No |  |
| `compatibility_flags` | [workers_compatibility_flags](workers-compatibility-flags.md) | No |  |
| `created_on` | string (date-time) | Yes | When the version was created. |
| `id` | string (uuid) | Yes | Version identifier. |
| `limits` | object | No | Resource limits enforced at runtime. |
| `main_module` | string | No | The name of the main module in the `modules` array (e.g. the name of the module that exports a `fetch` handler). |
| `migrations` | any | No | Migrations for Durable Objects associated with the version. Migrations are applied when the version is deployed. |
| `modules` | object[] | No | Code, sourcemaps, and other content used at runtime.

This includes [`_headers`](https://developers.cloudflare.com/workers/static-assets/headers/#custom-headers) and
[`_redirects`](https://developers.cloudflare.com/workers/static-assets/redirects/) files used to configure 
[Static Assets](https://developers.cloudflare.com/workers/static-assets/). `_headers` and `_redirects` files should be 
included as modules named `_headers` and `_redirects` with content type `text/plain`.
 |
| `number` | integer | Yes | The integer version number, starting from one. |
| `placement` | object | No | Placement settings for the version. |
| `source` | string | No | The client used to create the version. |
| `startup_time_ms` | integer | No | Time in milliseconds spent on [Worker startup](https://developers.cloudflare.com/workers/platform/limits/#worker-startup-time). |
| `usage_model` | enum: standard, bundled, unbound | No | Usage model for the version. |

## Nested Fields

### `annotations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `workers/message` | string | No | Human-readable message about the version. |
| `workers/tag` | string | No | User-provided identifier for the version. |
| `workers/triggered_by` | string | No | Operation that triggered the creation of the version. |

### `assets`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `config` | object | No | Configuration for assets within a Worker. |
| `jwt` | string | No | Token provided upon successful upload of all files from a registered manifest. |

#### `assets.config`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `html_handling` | enum: auto-trailing-slash, force-trailing-slash, drop-trailing-slash... | No | Determines the redirects and rewrites of requests for HTML content. |
| `not_found_handling` | enum: none, 404-page, single-page-application | No | Determines the response when a request does not match a static asset, and there is no Worker script. |
| `run_worker_first` | any | No |  |

### `limits`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cpu_ms` | integer | Yes | CPU time limit in milliseconds. |

### `modules`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `content_base64` | string (byte) | Yes | The base64-encoded module content. |
| `content_type` | string | Yes | The content type of the module. |
| `name` | string | Yes | The name of the module. |

### `placement`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `mode` | enum: smart | No | Placement mode for the version. |

