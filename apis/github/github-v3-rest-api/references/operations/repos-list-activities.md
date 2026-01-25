# GET /repos/{owner}/{repo}/activity

**Resource:** [repos](../resources/repos.md)
**List repository activities**
**Operation ID:** `repos/list-activities`

Lists a detailed history of changes to a repository, such as pushes, merges, force pushes, and branch changes, and associates these changes with commits and users.

For more information about viewing repository activity,
see "[Viewing activity and data for your repository](https://docs.github.com/repositories/viewing-activity-and-data-for-your-repository)."

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ref` | query | string | No | The Git reference for the activities you want to list.

The `ref` for a branch can be formatted either as `refs/heads/BRANCH_NAME` or `BRANCH_NAME`, where `BRANCH_NAME` is the name of your branch. |
| `actor` | query | string | No | The GitHub username to use to filter by the actor who performed the activity. |
| `time_period` | query | enum: day, week, month... | No | The time period to filter by.

For example, `day` will filter for activity that occurred in the past 24 hours, and `week` will filter for activity that occurred in the past 7 days (168 hours). |
| `activity_type` | query | enum: push, force_push, branch_creation... | No | The activity type to filter by.

For example, you can choose to filter by "force_push", to see all force pushes to the repository. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 422 | (reference) |

**Success Response Schema:**

Array of [activity](../schemas/activity/activity.md)

