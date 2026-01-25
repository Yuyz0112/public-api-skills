# ApplicationRole

Details of an application role.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultGroups` | string[] | No | The groups that are granted default access for this application role. As a group's name can change, use of `defaultGroupsDetails` is recommended to identify a groups. |
| `defaultGroupsDetails` | GroupName[] | No | The groups that are granted default access for this application role. |
| `defined` | boolean | No | Deprecated. |
| `groupDetails` | GroupName[] | No | The groups associated with the application role. |
| `groups` | string[] | No | The groups associated with the application role. As a group's name can change, use of `groupDetails` is recommended to identify a groups. |
| `hasUnlimitedSeats` | boolean | No |  |
| `key` | string | No | The key of the application role. |
| `name` | string | No | The display name of the application role. |
| `numberOfSeats` | integer (int32) | No | The maximum count of users on your license. |
| `platform` | boolean | No | Indicates if the application role belongs to Jira platform (`jira-core`). |
| `remainingSeats` | integer (int32) | No | The count of users remaining on your license. |
| `selectedByDefault` | boolean | No | Determines whether this application role should be selected by default on user creation. |
| `userCount` | integer (int32) | No | The number of users counting against your license. |
| `userCountDescription` | string | No | The [type of users](https://confluence.atlassian.com/x/lRW3Ng) being counted against your license. |

