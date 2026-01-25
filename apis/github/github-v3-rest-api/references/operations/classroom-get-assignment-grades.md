# GET /assignments/{assignment_id}/grades

**Resource:** [classroom](../resources/classroom.md)
**Get assignment grades**
**Operation ID:** `classroom/get-assignment-grades`

Gets grades for a GitHub Classroom assignment. Grades will only be returned if the current user is an administrator of the GitHub Classroom for the assignment.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [classroom-assignment-grade](../schemas/classroom-assignment-grade/classroom-assignment-grade.md)

