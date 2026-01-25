# RoleActor

Details about a user assigned to a project role.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actorGroup` | any | No |  |
| `actorUser` | any | No |  |
| `avatarUrl` | string (uri) | No | The avatar of the role actor. |
| `displayName` | string | No | The display name of the role actor. For users, depending on the user’s privacy setting, this may return an alternative value for the user's name. |
| `id` | integer (int64) | No | The ID of the role actor. |
| `name` | string | No | This property is no longer available and will be removed from the documentation soon. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `type` | enum: atlassian-group-role-actor, atlassian-user-role-actor | No | The type of role actor. |

