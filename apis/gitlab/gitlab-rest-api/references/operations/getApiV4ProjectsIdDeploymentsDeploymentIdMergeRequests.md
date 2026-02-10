# GET /api/v4/projects/{id}/deployments/{deployment_id}/merge_requests

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**List of merge requests associated with a deployment**
**Operation ID:** `getApiV4ProjectsIdDeploymentsDeploymentIdMergeRequests`

Retrieves the list of merge requests shipped with a given deployment. This feature was introduced in GitLab 12.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `deployment_id` | path | integer | Yes | The ID of the deployment |
| `author_id` | query | integer | No | Returns merge requests created by the given user `id`. Mutually exclusive with `author_username`. Combine with `scope=all` or `scope=assigned_to_me`. |
| `author_username` | query | string | No | Returns merge requests created by the given `username`. Mutually exclusive with `author_id`. |
| `assignee_id` | query | any | No | Returns merge requests assigned to the given user `id`. `None` returns unassigned merge requests. `Any` returns merge requests with an assignee. |
| `assignee_username` | query | any | No | Returns merge requests created by the given `username`. Mutually exclusive with `author_id`. |
| `reviewer_username` | query | string | No | Returns merge requests which have the user as a reviewer with the given `username`. `None` returns merge requests with no reviewers. `Any` returns merge requests with any reviewer. Mutually exclusive with `reviewer_id`. Introduced in GitLab 13.8. |
| `labels` | query | any | No | Returns merge requests matching a comma-separated list of labels. `None` lists all merge requests with no labels. `Any` lists all merge requests with at least one label. Predefined names are case-insensitive. |
| `milestone` | query | string | No | Returns merge requests for a specific milestone. `None` returns merge requests with no milestone. `Any` returns merge requests that have an assigned milestone. |
| `my_reaction_emoji` | query | string | No | Returns merge requests reacted by the authenticated user by the given `emoji`. `None` returns issues not given a reaction. `Any` returns issues given at least one reaction. |
| `reviewer_id` | query | any | No | Returns merge requests which have the user as a reviewer with the given user `id`. `None` returns merge requests with no reviewers. `Any` returns merge requests with any reviewer. Mutually exclusive with `reviewer_username`. |
| `state` | query | enum: opened, closed, locked... | No | Returns `all` merge requests or just those that are `opened`, `closed`, `locked`, or `merged`. |
| `order_by` | query | enum: created_at, label_priority, milestone_due... | No | Returns merge requests ordered by `created_at`, `label_priority`, `milestone_due`, `popularity`, `priority`, `title`, `updated_at` or `merged_at` fields. Introduced in GitLab 14.8. |
| `sort` | query | enum: asc, desc | No | Returns merge requests sorted in `asc` or `desc` order. |
| `with_labels_details` | query | boolean | No | If `true`, response returns more details for each label in labels field: `:name`,`:color`, `:description`, `:description_html`, `:text_color` |
| `with_merge_status_recheck` | query | boolean | No | If `true`, this projection requests (but does not guarantee) that the `merge_status` field be recalculated asynchronously. Introduced in GitLab 13.0. |
| `created_after` | query | string (date-time) | No | Returns merge requests created on or after the given time. Expected in ISO 8601 format. |
| `created_before` | query | string (date-time) | No | Returns merge requests created on or before the given time. Expected in ISO 8601 format. |
| `updated_after` | query | string (date-time) | No | Returns merge requests updated on or after the given time. Expected in ISO 8601 format. |
| `updated_before` | query | string (date-time) | No | Returns merge requests updated on or before the given time. Expected in ISO 8601 format. |
| `view` | query | enum: simple | No | If simple, returns the `iid`, URL, title, description, and basic state of merge request |
| `scope` | query | enum: created-by-me, assigned-to-me, created_by_me... | No | Returns merge requests for the given scope: `created_by_me`, `assigned_to_me`, `reviews_for_me` or `all` |
| `source_branch` | query | string | No | Returns merge requests with the given source branch |
| `source_project_id` | query | integer | No | Returns merge requests with the given source project id |
| `target_branch` | query | string | No | Returns merge requests with the given target branch |
| `search` | query | string | No | Search merge requests against their `title` and `description`. |
| `in` | query | string | No | Modify the scope of the search attribute. `title`, `description`, or a string joining them with comma. |
| `wip` | query | enum: yes, no | No | Filter merge requests against their `wip` status. `yes` to return only draft merge requests, `no` to return non-draft merge requests. |
| `not` | query | object | No | Returns merge requests that do not match the parameters supplied |
| `not[author_id]` | query | integer | No | `<Negated>` Returns merge requests created by the given user `id`. Mutually exclusive with `author_username`. Combine with `scope=all` or `scope=assigned_to_me`. |
| `not[author_username]` | query | string | No | `<Negated>` Returns merge requests created by the given `username`. Mutually exclusive with `author_id`. |
| `not[assignee_id]` | query | any | No | `<Negated>` Returns merge requests assigned to the given user `id`. `None` returns unassigned merge requests. `Any` returns merge requests with an assignee. |
| `not[assignee_username]` | query | any | No | `<Negated>` Returns merge requests created by the given `username`. Mutually exclusive with `author_id`. |
| `not[reviewer_username]` | query | string | No | `<Negated>` Returns merge requests which have the user as a reviewer with the given `username`. `None` returns merge requests with no reviewers. `Any` returns merge requests with any reviewer. Mutually exclusive with `reviewer_id`. Introduced in GitLab 13.8. |
| `not[labels]` | query | any | No | `<Negated>` Returns merge requests matching a comma-separated list of labels. `None` lists all merge requests with no labels. `Any` lists all merge requests with at least one label. Predefined names are case-insensitive. |
| `not[milestone]` | query | string | No | `<Negated>` Returns merge requests for a specific milestone. `None` returns merge requests with no milestone. `Any` returns merge requests that have an assigned milestone. |
| `not[my_reaction_emoji]` | query | string | No | `<Negated>` Returns merge requests reacted by the authenticated user by the given `emoji`. `None` returns issues not given a reaction. `Any` returns issues given at least one reaction. |
| `not[reviewer_id]` | query | integer | No | `<Negated>` Returns merge requests which have the user as a reviewer with the given user `id`. `None` returns merge requests with no reviewers. `Any` returns merge requests with any reviewer. Mutually exclusive with `reviewer_username`. |
| `deployed_before` | query | string | No | Returns merge requests deployed before the given date/time. Expected in ISO 8601 format. |
| `deployed_after` | query | string | No | Returns merge requests deployed after the given date/time. Expected in ISO 8601 format |
| `environment` | query | string | No | Returns merge requests deployed to the given environment |
| `approved` | query | enum: yes, no | No | Filters merge requests by their `approved` status. `yes` returns only approved merge requests. `no` returns only non-approved merge requests. |
| `merge_user_id` | query | integer | No | Returns merge requests which have been merged by the user with the given user `id`. Mutually exclusive with `merge_user_username`. |
| `merge_user_username` | query | string | No | Returns merge requests which have been merged by the user with the given `username`. Mutually exclusive with `merge_user_id`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesMergeRequestBasic](../schemas/APIEntitiesMergeRequestBasic/APIEntitiesMergeRequestBasic.md)

