# GET /repos/{owner}/{repo}/milestones

**Resource:** [issues](../resources/issues.md)
**List milestones**
**Operation ID:** `issues/list-milestones`

Lists milestones for a repository.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `state` | query | enum: open, closed, all | No | The state of the milestone. Either `open`, `closed`, or `all`. |
| `sort` | query | enum: due_on, completeness | No | What to sort results by. Either `due_on` or `completeness`. |
| `direction` | query | enum: asc, desc | No | The direction of the sort. Either `asc` or `desc`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [milestone](../schemas/milestone/milestone.md)

