# GET /repos/{owner}/{repo}/issues/{issue_number}/assignees/{assignee}

**Resource:** [issues](../resources/issues.md)
**Check if a user can be assigned to a issue**
**Operation ID:** `issues/check-user-can-be-assigned-to-issue`

Checks if a user has permission to be assigned to a specific issue.

If the `assignee` can be assigned to this issue, a `204` status code with no content is returned.

Otherwise a `404` status code is returned.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `assignee` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response if `assignee` can be assigned to `issue_number` |
| 404 | Response if `assignee` can not be assigned to `issue_number` |

