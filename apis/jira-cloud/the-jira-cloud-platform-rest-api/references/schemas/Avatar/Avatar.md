# Avatar

Details of an avatar.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fileName` | string | No | The file name of the avatar icon. Returned for system avatars. |
| `id` | string | Yes | The ID of the avatar. |
| `isDeletable` | boolean | No | Whether the avatar can be deleted. |
| `isSelected` | boolean | No | Whether the avatar is used in Jira. For example, shown as a project's avatar. |
| `isSystemAvatar` | boolean | No | Whether the avatar is a system avatar. |
| `owner` | string | No | The owner of the avatar. For a system avatar the owner is null (and nothing is returned). For non-system avatars this is the appropriate identifier, such as the ID for a project or the account ID for a user. |
| `urls` | object | No | The list of avatar icon URLs. |

