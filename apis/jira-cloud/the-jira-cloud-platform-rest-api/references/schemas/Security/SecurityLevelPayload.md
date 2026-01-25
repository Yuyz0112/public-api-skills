# SecurityLevelPayload

The payload for creating a security level. See https://support.atlassian.com/jira-cloud-administration/docs/configure-issue-security-schemes/

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the security level |
| `isDefault` | enum: true, false | No | Whether the security level is default for the security scheme |
| `name` | string | No | The name of the security level |
| `securityLevelMembers` | SecurityLevelMemberPayload[] | No | The members of the security level |

