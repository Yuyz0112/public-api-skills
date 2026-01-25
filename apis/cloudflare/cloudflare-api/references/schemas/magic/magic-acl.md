# magic_acl

Bidirectional ACL policy for network traffic within a site.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | Description for the ACL. |
| `forward_locally` | [magic_forward_locally](magic-forward-locally.md) | No |  |
| `id` | [magic_identifier](magic-identifier.md) | No |  |
| `lan_1` | [magic_lan-acl-configuration](magic-lan-acl-configuration.md) | No |  |
| `lan_2` | [magic_lan-acl-configuration](magic-lan-acl-configuration.md) | No |  |
| `name` | string | No | The name of the ACL. |
| `protocols` | string[] | No |  |
| `unidirectional` | [magic_unidirectional](magic-unidirectional.md) | No |  |

