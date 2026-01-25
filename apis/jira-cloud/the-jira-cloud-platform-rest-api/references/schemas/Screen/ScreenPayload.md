# ScreenPayload

Defines the payload for the field screens. See https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-screens/\#api-rest-api-3-screens-post

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the screen |
| `name` | string | No | The name of the screen |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `tabs` | TabPayload[] | No | The tabs of the screen. See https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-screen-tab-fields/\#api-rest-api-3-screens-screenid-tabs-tabid-fields-post |

