# ScreenSchemePayload

Defines the payload for the screen schemes. See https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-screen-schemes/\#api-rest-api-3-screenscheme-post

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultScreen` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `description` | string | No | The description of the screen scheme |
| `name` | string | No | The name of the screen scheme |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `screens` | object | No | Similar to the field layout scheme those mappings allow users to set different screens for different operations: default - always there, applied to all operations that don't have an explicit mapping `create`, `view`, `edit` - specific operations that are available and users can assign a different screen for each one of them https://support.atlassian.com/jira-cloud-administration/docs/manage-screen-schemes/\#Associating-a-screen-with-an-issue-operation |

