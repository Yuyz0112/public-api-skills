# NewUserDetails

The user details.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `applicationKeys` | string[] | No | Deprecated, do not use. |
| `displayName` | string | No | This property is no longer available. If the user has an Atlassian account, their display name is not changed. If the user does not have an Atlassian account, they are sent an email asking them set up an account. |
| `emailAddress` | string | Yes | The email address for the user. |
| `key` | string | No | This property is no longer available. See the [migration guide](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `name` | string | No | This property is no longer available. See the [migration guide](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `password` | string | No | This property is no longer available. If the user has an Atlassian account, their password is not changed. If the user does not have an Atlassian account, they are sent an email asking them set up an account. |
| `products` | string[] | Yes | Products the new user has access to. Valid products are: jira-core, jira-servicedesk, jira-product-discovery, jira-software. To create a user without product access, set this field to be an empty array. |
| `self` | string | No | The URL of the user. |

