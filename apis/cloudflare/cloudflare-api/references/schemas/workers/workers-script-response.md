# workers_script-response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `compatibility_date` | [workers_compatibility_date](workers-compatibility-date.md) | No |  |
| `compatibility_flags` | [workers_compatibility_flags](workers-compatibility-flags.md) | No |  |
| `created_on` | [workers_created_on](workers-created-on.md) | No |  |
| `etag` | [workers_etag](workers-etag.md) | No |  |
| `handlers` | string[] | No | The names of handlers exported as part of the default export. |
| `has_assets` | [workers_has_assets](workers-has-assets.md) | No |  |
| `has_modules` | [workers_has_modules](workers-has-modules.md) | No |  |
| `id` | string | No | The name used to identify the script. |
| `last_deployed_from` | string | No | The client most recently used to deploy this Worker. |
| `logpush` | [workers_logpush](workers-logpush.md) | No |  |
| `migration_tag` | string | No | The tag of the Durable Object migration that was most recently applied for this Worker. |
| `modified_on` | [workers_modified_on](workers-modified-on.md) | No |  |
| `named_handlers` | object[] | No | Named exports, such as Durable Object class implementations and named entrypoints. |
| `observability` | [workers_observability](workers-observability.md) | No |  |
| `placement` | [workers_placement_info](workers-placement-info.md) | No |  |
| `placement_mode` | any | No |  |
| `placement_status` | any | No |  |
| `tag` | string | No | The immutable ID of the script. |
| `tags` | [workers_tags](workers-tags.md) | No |  |
| `tail_consumers` | [workers_tail_consumers](workers-tail-consumers.md) | No |  |
| `usage_model` | [workers_usage_model](workers-usage-model.md) | No |  |

## Nested Fields

### `named_handlers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `handlers` | string[] | No | The names of handlers exported as part of the named export. |
| `name` | string | No | The name of the export. |

