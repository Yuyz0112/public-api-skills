# workers_binding_kind_secrets_store_secret

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | [workers_binding_name](workers-binding-name.md) | Yes |  |
| `secret_name` | string | Yes | Name of the secret in the store. |
| `store_id` | string | Yes | ID of the store containing the secret. |
| `type` | enum: secrets_store_secret | Yes | The kind of resource that the binding provides. |

