# POST /repos/{owner}/{repo}/milestones

**Resource:** [issues](../resources/issues.md)
**Create a milestone**
**Operation ID:** `issues/create-milestone`

Creates a milestone.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[milestone](../schemas/milestone/milestone.md)

