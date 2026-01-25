# ProjectRole

Details about the roles in a project.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actors` | RoleActor[] | No | The list of users who act in this role. |
| `admin` | boolean | No | Whether this role is the admin role for the project. |
| `currentUserRole` | boolean | No | Whether the calling user is part of this role. |
| `default` | boolean | No | Whether this role is the default role for the project |
| `description` | string | No | The description of the project role. |
| `id` | integer (int64) | No | The ID of the project role. |
| `name` | string | No | The name of the project role. |
| `roleConfigurable` | boolean | No | Whether the roles are configurable for this project. |
| `scope` | any | No | The scope of the role. Indicated for roles associated with [next-gen projects](https://confluence.atlassian.com/x/loMyO). |
| `self` | string (uri) | No | The URL the project role details. |
| `translatedName` | string | No | The translated name of the project role. |

