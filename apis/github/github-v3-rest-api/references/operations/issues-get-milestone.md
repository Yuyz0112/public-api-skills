# GET /repos/{owner}/{repo}/milestones/{milestone_number}

**Resource:** [issues](../resources/issues.md)
**Get a milestone**
**Operation ID:** `issues/get-milestone`

Gets a milestone using the given milestone number.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[milestone](../schemas/milestone/milestone.md)

