# POST /goals/{goal_gid}/addCustomFieldSetting

**Resource:** [Goals](../resources/Goals.md)
**Add a custom field to a goal**
**Operation ID:** `addCustomFieldSettingForGoal`

<b>Required scope: </b><code>goals:write</code>

Custom fields are associated with goals by way of custom field settings.  This method creates a setting for the goal.

## Request Body

Information about the custom field setting.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added the custom field to the goal. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: goals:write
