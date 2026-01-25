# workers_multipart-script

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `files` | string[] | No | An array of modules (often JavaScript files) comprising a Worker script. At least one module must be present and referenced in the metadata as `main_module` or `body_part` by filename.<br/>Possible Content-Type(s) are: `application/javascript+module`, `text/javascript+module`, `application/javascript`, `text/javascript`, `text/x-python`, `text/x-python-requirement`, `application/wasm`, `text/plain`, `application/octet-stream`, `application/source-map`. |
| `metadata` | object | Yes | JSON-encoded metadata about the uploaded parts and Worker configuration. |

## Nested Fields

### `metadata`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `assets` | [workers_assets](workers-assets.md) | No |  |
| `bindings` | [workers_bindings](workers-bindings.md) | No |  |
| `body_part` | string | No | Name of the uploaded file that contains the script (e.g. the file adding a listener to the `fetch` event). Indicates a `service worker syntax` Worker. |
| `compatibility_date` | [workers_compatibility_date](workers-compatibility-date.md) | No |  |
| `compatibility_flags` | [workers_compatibility_flags](workers-compatibility-flags.md) | No |  |
| `keep_assets` | boolean | No | Retain assets which exist for a previously uploaded Worker version; used in lieu of providing a completion token. |
| `keep_bindings` | string[] | No | List of binding types to keep from previous_upload. |
| `limits` | [workers_limits](workers-limits.md) | No |  |
| `logpush` | [workers_logpush](workers-logpush.md) | No |  |
| `main_module` | string | No | Name of the uploaded file that contains the main module (e.g. the file exporting a `fetch` handler). Indicates a `module syntax` Worker. |
| `migrations` | any | No | Migrations to apply for Durable Objects associated with this Worker. |
| `observability` | [workers_observability](workers-observability.md) | No |  |
| `placement` | [workers_placement_info](workers-placement-info.md) | No |  |
| `tags` | string[] | No | List of strings to use as tags for this Worker. |
| `tail_consumers` | [workers_tail_consumers](workers-tail-consumers.md) | No |  |
| `usage_model` | [workers_usage_model](workers-usage-model.md) | No |  |

