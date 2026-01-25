# FieldCapabilityPayload

Defines the payload for the fields, screens, screen schemes, issue type screen schemes, field layouts, and field layout schemes

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `customFieldDefinitions` | CustomFieldPayload[] | No | The custom field definitions. See https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-fields/\#api-rest-api-3-field-post |
| `fieldLayoutScheme` | [FieldLayoutSchemePayload](FieldLayoutSchemePayload.md) | No |  |
| `fieldLayouts` | FieldLayoutPayload[] | No | The field layouts configuration. |
| `issueLayouts` | IssueLayoutPayload[] | No | The issue layouts configuration |
| `issueTypeScreenScheme` | [IssueTypeScreenSchemePayload](IssueTypeScreenSchemePayload.md) | No |  |
| `screenScheme` | ScreenSchemePayload[] | No | The screen schemes See https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-screen-schemes/\#api-rest-api-3-screenscheme-post |
| `screens` | ScreenPayload[] | No | The screens. See https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-screens/\#api-rest-api-3-screens-post |

