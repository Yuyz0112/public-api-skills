# workers_binding_kind_r2_bucket

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bucket_name` | string | Yes | R2 bucket to bind to. |
| `jurisdiction` | enum: eu, fedramp | No | The [jurisdiction](https://developers.cloudflare.com/r2/reference/data-location/#jurisdictional-restrictions) of the R2 bucket. |
| `name` | [workers_binding_name](workers-binding-name.md) | Yes |  |
| `type` | enum: r2_bucket | Yes | The kind of resource that the binding provides. |

