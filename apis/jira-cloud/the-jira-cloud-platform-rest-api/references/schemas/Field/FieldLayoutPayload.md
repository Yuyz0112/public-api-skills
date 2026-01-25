# FieldLayoutPayload

Defines the payload for the field layouts. See https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-field-configurations/\#api-group-issue-field-configurations" + fieldlayout is what users would see as "Field Configuration" in Jira's UI - https://support.atlassian.com/jira-cloud-administration/docs/manage-issue-field-configurations/

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `configuration` | FieldLayoutConfiguration[] | No | The field layout configuration. See https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-field-configurations/\#api-rest-api-3-fieldconfiguration-post |
| `description` | string | No | The description of the field layout |
| `name` | string | No | The name of the field layout |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |

