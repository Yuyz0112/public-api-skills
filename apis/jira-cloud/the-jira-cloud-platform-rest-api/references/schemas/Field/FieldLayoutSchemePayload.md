# FieldLayoutSchemePayload

Defines the payload for the field layout schemes. See "Field Configuration Scheme" - https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-field-configurations/\#api-rest-api-3-fieldconfigurationscheme-post https://support.atlassian.com/jira-cloud-administration/docs/configure-a-field-configuration-scheme/

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultFieldLayout` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `description` | string | No | The description of the field layout scheme |
| `explicitMappings` | object | No | There is a default configuration "fieldlayout" that is applied to all issue types using this scheme that don't have an explicit mapping users can create (or re-use existing) configurations for other issue types and map them to this scheme |
| `name` | string | No | The name of the field layout scheme |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |

