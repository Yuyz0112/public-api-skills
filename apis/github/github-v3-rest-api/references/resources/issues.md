# issues

Interact with GitHub Issues.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/issues` | List issues assigned to the authenticated user | [View](../operations/issues-list.md) |
| GET | `/orgs/{org}/issues` | List organization issues assigned to the authenticated user | [View](../operations/issues-list-for-org.md) |
| GET | `/repos/{owner}/{repo}/assignees` | List assignees | [View](../operations/issues-list-assignees.md) |
| GET | `/repos/{owner}/{repo}/assignees/{assignee}` | Check if a user can be assigned | [View](../operations/issues-check-user-can-be-assigned.md) |
| GET | `/repos/{owner}/{repo}/issues` | List repository issues | [View](../operations/issues-list-for-repo.md) |
| POST | `/repos/{owner}/{repo}/issues` | Create an issue | [View](../operations/issues-create.md) |
| GET | `/repos/{owner}/{repo}/issues/comments` | List issue comments for a repository | [View](../operations/issues-list-comments-for-repo.md) |
| GET | `/repos/{owner}/{repo}/issues/comments/{comment_id}` | Get an issue comment | [View](../operations/issues-get-comment.md) |
| DELETE | `/repos/{owner}/{repo}/issues/comments/{comment_id}` | Delete an issue comment | [View](../operations/issues-delete-comment.md) |
| PATCH | `/repos/{owner}/{repo}/issues/comments/{comment_id}` | Update an issue comment | [View](../operations/issues-update-comment.md) |
| GET | `/repos/{owner}/{repo}/issues/events` | List issue events for a repository | [View](../operations/issues-list-events-for-repo.md) |
| GET | `/repos/{owner}/{repo}/issues/events/{event_id}` | Get an issue event | [View](../operations/issues-get-event.md) |
| GET | `/repos/{owner}/{repo}/issues/{issue_number}` | Get an issue | [View](../operations/issues-get.md) |
| PATCH | `/repos/{owner}/{repo}/issues/{issue_number}` | Update an issue | [View](../operations/issues-update.md) |
| POST | `/repos/{owner}/{repo}/issues/{issue_number}/assignees` | Add assignees to an issue | [View](../operations/issues-add-assignees.md) |
| DELETE | `/repos/{owner}/{repo}/issues/{issue_number}/assignees` | Remove assignees from an issue | [View](../operations/issues-remove-assignees.md) |
| GET | `/repos/{owner}/{repo}/issues/{issue_number}/assignees/{assignee}` | Check if a user can be assigned to a issue | [View](../operations/issues-check-user-can-be-assigned-to-issue.md) |
| GET | `/repos/{owner}/{repo}/issues/{issue_number}/comments` | List issue comments | [View](../operations/issues-list-comments.md) |
| POST | `/repos/{owner}/{repo}/issues/{issue_number}/comments` | Create an issue comment | [View](../operations/issues-create-comment.md) |
| GET | `/repos/{owner}/{repo}/issues/{issue_number}/dependencies/blocked_by` | List dependencies an issue is blocked by | [View](../operations/issues-list-dependencies-blocked-by.md) |
| POST | `/repos/{owner}/{repo}/issues/{issue_number}/dependencies/blocked_by` | Add a dependency an issue is blocked by | [View](../operations/issues-add-blocked-by-dependency.md) |
| DELETE | `/repos/{owner}/{repo}/issues/{issue_number}/dependencies/blocked_by/{issue_id}` | Remove dependency an issue is blocked by | [View](../operations/issues-remove-dependency-blocked-by.md) |
| GET | `/repos/{owner}/{repo}/issues/{issue_number}/dependencies/blocking` | List dependencies an issue is blocking | [View](../operations/issues-list-dependencies-blocking.md) |
| GET | `/repos/{owner}/{repo}/issues/{issue_number}/events` | List issue events | [View](../operations/issues-list-events.md) |
| GET | `/repos/{owner}/{repo}/issues/{issue_number}/labels` | List labels for an issue | [View](../operations/issues-list-labels-on-issue.md) |
| PUT | `/repos/{owner}/{repo}/issues/{issue_number}/labels` | Set labels for an issue | [View](../operations/issues-set-labels.md) |
| POST | `/repos/{owner}/{repo}/issues/{issue_number}/labels` | Add labels to an issue | [View](../operations/issues-add-labels.md) |
| DELETE | `/repos/{owner}/{repo}/issues/{issue_number}/labels` | Remove all labels from an issue | [View](../operations/issues-remove-all-labels.md) |
| DELETE | `/repos/{owner}/{repo}/issues/{issue_number}/labels/{name}` | Remove a label from an issue | [View](../operations/issues-remove-label.md) |
| PUT | `/repos/{owner}/{repo}/issues/{issue_number}/lock` | Lock an issue | [View](../operations/issues-lock.md) |
| DELETE | `/repos/{owner}/{repo}/issues/{issue_number}/lock` | Unlock an issue | [View](../operations/issues-unlock.md) |
| GET | `/repos/{owner}/{repo}/issues/{issue_number}/parent` | Get parent issue | [View](../operations/issues-get-parent.md) |
| DELETE | `/repos/{owner}/{repo}/issues/{issue_number}/sub_issue` | Remove sub-issue | [View](../operations/issues-remove-sub-issue.md) |
| GET | `/repos/{owner}/{repo}/issues/{issue_number}/sub_issues` | List sub-issues | [View](../operations/issues-list-sub-issues.md) |
| POST | `/repos/{owner}/{repo}/issues/{issue_number}/sub_issues` | Add sub-issue | [View](../operations/issues-add-sub-issue.md) |
| PATCH | `/repos/{owner}/{repo}/issues/{issue_number}/sub_issues/priority` | Reprioritize sub-issue | [View](../operations/issues-reprioritize-sub-issue.md) |
| GET | `/repos/{owner}/{repo}/issues/{issue_number}/timeline` | List timeline events for an issue | [View](../operations/issues-list-events-for-timeline.md) |
| GET | `/repos/{owner}/{repo}/labels` | List labels for a repository | [View](../operations/issues-list-labels-for-repo.md) |
| POST | `/repos/{owner}/{repo}/labels` | Create a label | [View](../operations/issues-create-label.md) |
| GET | `/repos/{owner}/{repo}/labels/{name}` | Get a label | [View](../operations/issues-get-label.md) |
| DELETE | `/repos/{owner}/{repo}/labels/{name}` | Delete a label | [View](../operations/issues-delete-label.md) |
| PATCH | `/repos/{owner}/{repo}/labels/{name}` | Update a label | [View](../operations/issues-update-label.md) |
| GET | `/repos/{owner}/{repo}/milestones` | List milestones | [View](../operations/issues-list-milestones.md) |
| POST | `/repos/{owner}/{repo}/milestones` | Create a milestone | [View](../operations/issues-create-milestone.md) |
| GET | `/repos/{owner}/{repo}/milestones/{milestone_number}` | Get a milestone | [View](../operations/issues-get-milestone.md) |
| DELETE | `/repos/{owner}/{repo}/milestones/{milestone_number}` | Delete a milestone | [View](../operations/issues-delete-milestone.md) |
| PATCH | `/repos/{owner}/{repo}/milestones/{milestone_number}` | Update a milestone | [View](../operations/issues-update-milestone.md) |
| GET | `/repos/{owner}/{repo}/milestones/{milestone_number}/labels` | List labels for issues in a milestone | [View](../operations/issues-list-labels-for-milestone.md) |
| GET | `/user/issues` | List user account issues assigned to the authenticated user | [View](../operations/issues-list-for-authenticated-user.md) |
