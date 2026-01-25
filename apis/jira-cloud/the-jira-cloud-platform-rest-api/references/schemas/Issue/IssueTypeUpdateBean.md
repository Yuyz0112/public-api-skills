# IssueTypeUpdateBean

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatarId` | integer (int64) | No | The ID of an issue type avatar. This can be obtained be obtained from the following endpoints:

 *  [System issue type avatar IDs only](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-avatars/#api-rest-api-3-avatar-type-system-get)
 *  [System and custom issue type avatar IDs](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-avatars/#api-rest-api-3-universal-avatar-type-type-owner-entityid-get) |
| `description` | string | No | The description of the issue type. |
| `name` | string | No | The unique name for the issue type. The maximum length is 60 characters. |

