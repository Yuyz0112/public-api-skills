# ProjectRoleDetails

Details about a project role.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `admin` | boolean | No | Whether this role is the admin role for the project. |
| `default` | boolean | No | Whether this role is the default role for the project. |
| `description` | string | No | The description of the project role. |
| `id` | integer (int64) | No | The ID of the project role. |
| `name` | string | No | The name of the project role. |
| `roleConfigurable` | boolean | No | Whether the roles are configurable for this project. |
| `scope` | any | No | The scope of the role. Indicated for roles associated with [next-gen projects](https://confluence.atlassian.com/x/loMyO). |
| `self` | string (uri) | No | The URL the project role details. |
| `translatedName` | string | No | The translated name of the project role. |
| `type` | enum: DEFAULT, GUEST_ROLE | No | The type of the project role. This is "DEFAULT" or "GUEST\_ROLE". |

