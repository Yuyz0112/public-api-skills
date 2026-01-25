# POST /goals/{goal_gid}/removeCustomFieldSetting

**Resource:** [Goals](../resources/Goals.md)
**Remove a custom field from a goal**
**Operation ID:** `removeCustomFieldSettingForGoal`

<b>Required scope: </b><code>goals:write</code>

Removes a custom field setting from a goal.

## Request Body

Information about the custom field setting being removed.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully removed the custom field from the goal. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: goals:write
