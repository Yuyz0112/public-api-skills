# GET /repos/{owner}/{repo}/assignees/{assignee}

**Resource:** [issues](../resources/issues.md)
**Check if a user can be assigned**
**Operation ID:** `issues/check-user-can-be-assigned`

Checks if a user has permission to be assigned to an issue in this repository.

If the `assignee` can be assigned to issues in the repository, a `204` header with no content is returned.

Otherwise a `404` status code is returned.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `assignee` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | If the `assignee` can be assigned to issues in the repository, a `204` header with no content is returned. |
| 404 | Otherwise a `404` status code is returned. |

