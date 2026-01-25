# magic_acls_add_single_request

Bidirectional ACL policy for local network traffic within a site.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | Description for the ACL. |
| `forward_locally` | [magic_forward_locally](magic-forward-locally.md) | No |  |
| `lan_1` | [magic_lan-acl-configuration](magic-lan-acl-configuration.md) | Yes |  |
| `lan_2` | [magic_lan-acl-configuration](magic-lan-acl-configuration.md) | Yes |  |
| `name` | string | Yes | The name of the ACL. |
| `protocols` | string[] | No |  |
| `unidirectional` | [magic_unidirectional](magic-unidirectional.md) | No |  |

