# org-membership

Org Membership

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `state` | enum: active, pending | Yes | The state of the member in the organization. The `pending` state indicates the user has not yet accepted an invitation. |
| `role` | enum: admin, member, billing_manager | Yes | The user's membership type in the organization. |
| `direct_membership` | boolean | No | Whether the user has direct membership in the organization. |
| `enterprise_teams_providing_indirect_membership` | string[] | No | The slugs of the enterprise teams providing the user with indirect membership in the organization.
A limit of 100 enterprise team slugs is returned. |
| `organization_url` | string (uri) | Yes |  |
| `organization` | [organization-simple](organization-simple.md) | Yes |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `permissions` | object | No |  |

## Nested Fields

### `permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_create_repository` | boolean | Yes |  |

