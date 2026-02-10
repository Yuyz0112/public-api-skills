# GET /api/v4/projects/{id}/issues_statistics

**Resource:** [Projects](../resources/Projects.md)
**Get statistics for the list of project issues**
**Operation ID:** `getApiV4ProjectsIdIssuesStatistics`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `labels` | query | any | No | Comma-separated list of label names |
| `milestone` | query | string | No | Milestone title |
| `milestone_id` | query | enum: Any, None, Upcoming... | No | Return issues assigned to milestones with the specified timebox value ("Any", "None", "Upcoming" or "Started") |
| `iids` | query | any | No | The IID array of issues |
| `search` | query | string | No | Search issues for text present in the title, description, or any combination of these |
| `in` | query | string | No | `title`, `description`, or a string joining them with comma |
| `author_id` | query | integer | No | Return issues which are authored by the user with the given ID |
| `author_username` | query | string | No | Return issues which are authored by the user with the given username |
| `assignee_id` | query | any | No | Return issues which are assigned to the user with the given ID |
| `assignee_username` | query | any | No | Return issues which are assigned to the user with the given username |
| `created_after` | query | string (date-time) | No | Return issues created after the specified time |
| `created_before` | query | string (date-time) | No | Return issues created before the specified time |
| `updated_after` | query | string (date-time) | No | Return issues updated after the specified time |
| `updated_before` | query | string (date-time) | No | Return issues updated before the specified time |
| `not` | query | object | No | Filters by the specified parameters |
| `not[labels]` | query | any | No | Comma-separated list of label names |
| `not[milestone]` | query | string | No | Milestone title |
| `not[milestone_id]` | query | enum: Any, None, Upcoming... | No | Return issues assigned to milestones without the specified timebox value ("Any", "None", "Upcoming" or "Started") |
| `not[iids]` | query | any | No | The IID array of issues |
| `not[author_id]` | query | integer | No | Return issues which are not authored by the user with the given ID |
| `not[author_username]` | query | string | No | Return issues which are not authored by the user with the given username |
| `not[assignee_id]` | query | integer | No | Return issues which are not assigned to the user with the given ID |
| `not[assignee_username]` | query | any | No | Return issues which are not assigned to the user with the given username |
| `not[weight]` | query | integer | No | Return issues without the specified weight |
| `not[iteration_id]` | query | any | No | Return issues which are not assigned to the iteration with the given ID |
| `not[iteration_title]` | query | string | No | Return issues which are not assigned to the iteration with the given title |
| `scope` | query | enum: created-by-me, assigned-to-me, created_by_me... | No | Return issues for the given scope: `created_by_me`, `assigned_to_me` or `all` |
| `my_reaction_emoji` | query | string | No | Return issues reacted by the authenticated user by the given emoji |
| `confidential` | query | boolean | No | Filter confidential or public issues |
| `weight` | query | any | No | The weight of the issue |
| `epic_id` | query | any | No | The ID of an epic associated with the issues |
| `health_status` | query | enum: on_track, needs_attention, at_risk... | No | The health status of the issue. Must be one of: on_track, needs_attention, at_risk, none, any |
| `iteration_id` | query | any | No | Return issues which are assigned to the iteration with the given ID |
| `iteration_title` | query | string | No | Return issues which are assigned to the iteration with the given title |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

