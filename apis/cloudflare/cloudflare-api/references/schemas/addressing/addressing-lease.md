# addressing_lease

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active_from` | string (date-time) | No | Timestamp of the moment the lease was created.
 |
| `cidrs` | addressing_schemas-cidr[] | No | CIDRs attached to the lease |
| `created_at` | [addressing_created_at](addressing-created-at.md) | No |  |
| `id` | [addressing_lease_id](addressing-lease-id.md) | No |  |
| `modified_at` | [addressing_modified_at](addressing-modified-at.md) | No |  |
| `owner_id` | [addressing_lease_owner_id](addressing-lease-owner-id.md) | No |  |
| `purpose` | string | No | Describes the purpose of the addresses. |

