# SecuritySchemePayload

The payload for creating a security scheme. See https://support.atlassian.com/jira-cloud-administration/docs/configure-issue-security-schemes/

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the security scheme |
| `name` | string | No | The name of the security scheme |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `securityLevels` | SecurityLevelPayload[] | No | The security levels for the security scheme |

