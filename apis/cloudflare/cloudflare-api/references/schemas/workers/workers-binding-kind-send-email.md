# workers_binding_kind_send_email

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allowed_destination_addresses` | string[] | No | List of allowed destination addresses. |
| `allowed_sender_addresses` | string[] | No | List of allowed sender addresses. |
| `destination_address` | string (email) | No | Destination address for the email. |
| `name` | [workers_binding_name](workers-binding-name.md) | Yes |  |
| `type` | enum: send_email | Yes | The kind of resource that the binding provides. |

