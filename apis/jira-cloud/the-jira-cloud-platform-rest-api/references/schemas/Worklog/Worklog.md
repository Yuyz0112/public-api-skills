# Worklog

Details of a worklog.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author` | any | No | Details of the user who created the worklog. |
| `comment` | any | No | A comment about the worklog in [Atlassian Document Format](https://developer.atlassian.com/cloud/jira/platform/apis/document/structure/). Optional when creating or updating a worklog. |
| `created` | string (date-time) | No | The datetime on which the worklog was created. |
| `id` | string | No | The ID of the worklog record. |
| `issueId` | string | No | The ID of the issue this worklog is for. |
| `properties` | EntityProperty[] | No | Details of properties for the worklog. Optional when creating or updating a worklog. |
| `self` | string (uri) | No | The URL of the worklog item. |
| `started` | string (date-time) | No | The datetime on which the worklog effort was started. Required when creating a worklog. Optional when updating a worklog. |
| `timeSpent` | string | No | The time spent working on the issue as days (\#d), hours (\#h), or minutes (\#m or \#). Required when creating a worklog if `timeSpentSeconds` isn't provided. Optional when updating a worklog. Cannot be provided if `timeSpentSecond` is provided. |
| `timeSpentSeconds` | integer (int64) | No | The time in seconds spent working on the issue. Required when creating a worklog if `timeSpent` isn't provided. Optional when updating a worklog. Cannot be provided if `timeSpent` is provided. |
| `updateAuthor` | any | No | Details of the user who last updated the worklog. |
| `updated` | string (date-time) | No | The datetime on which the worklog was last updated. |
| `visibility` | any | No | Details about any restrictions in the visibility of the worklog. Optional when creating or updating a worklog. |

