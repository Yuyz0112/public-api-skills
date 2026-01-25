# UserPickerUser

A user found in a search.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accountId` | string | No | The account ID of the user, which uniquely identifies the user across all Atlassian products. For example, *5b10ac8d82e05b22cc7d4ef5*. |
| `accountType` | enum: atlassian, app, customer... | No | The user account type. Can take the following values:

 *  `atlassian` regular Atlassian user account
 *  `app` system account used for Connect applications and OAuth to represent external systems
 *  `customer` Jira Service Desk account representing an external service desk |
| `avatarUrl` | string (uri) | No | The avatar URL of the user. |
| `displayName` | string | No | The display name of the user. Depending on the user’s privacy setting, this may be returned as null. |
| `html` | string | No | The display name, email address, and key of the user with the matched query string highlighted with the HTML bold tag. |
| `key` | string | No | This property is no longer available. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `name` | string | No | This property is no longer available . See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |

