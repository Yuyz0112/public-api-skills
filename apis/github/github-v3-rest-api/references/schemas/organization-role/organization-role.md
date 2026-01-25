# organization-role

Organization roles

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes | The unique identifier of the role. |
| `name` | string | Yes | The name of the role. |
| `description` | string | No | A short description about who this role is for or what permissions it grants. |
| `base_role` | enum: read, triage, write... | No | The system role from which this role inherits permissions. |
| `source` | enum: Organization, Enterprise, Predefined | No | Source answers the question, "where did this role come from?" |
| `permissions` | string[] | Yes | A list of permissions included in this role. |
| `organization` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `created_at` | string (date-time) | Yes | The date and time the role was created. |
| `updated_at` | string (date-time) | Yes | The date and time the role was last updated. |

