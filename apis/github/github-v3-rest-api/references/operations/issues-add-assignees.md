# POST /repos/{owner}/{repo}/issues/{issue_number}/assignees

**Resource:** [issues](../resources/issues.md)
**Add assignees to an issue**
**Operation ID:** `issues/add-assignees`

Adds up to 10 assignees to an issue. Users already assigned to an issue are not replaced.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

**Success Response Schema:**

[issue](../schemas/issue/issue.md)

