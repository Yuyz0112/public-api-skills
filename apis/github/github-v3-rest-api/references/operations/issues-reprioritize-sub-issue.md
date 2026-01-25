# PATCH /repos/{owner}/{repo}/issues/{issue_number}/sub_issues/priority

**Resource:** [issues](../resources/issues.md)
**Reprioritize sub-issue**
**Operation ID:** `issues/reprioritize-sub-issue`

You can use the REST API to reprioritize a sub-issue to a different position in the parent list.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[issue](../schemas/issue/issue.md)

