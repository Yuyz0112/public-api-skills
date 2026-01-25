# UserBean

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accountId` | string | No | The account ID of the user, which uniquely identifies the user across all Atlassian products. For example, *5b10ac8d82e05b22cc7d4ef5*. |
| `active` | boolean | No | Whether the user is active. |
| `avatarUrls` | any | No | The avatars of the user. |
| `displayName` | string | No | The display name of the user. Depending on the user’s privacy setting, this may return an alternative value. |
| `key` | string | No | This property is deprecated in favor of `accountId` because of privacy changes. See the [migration guide](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details.  
The key of the user. |
| `name` | string | No | This property is deprecated in favor of `accountId` because of privacy changes. See the [migration guide](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details.  
The username of the user. |
| `self` | string (uri) | No | The URL of the user. |

