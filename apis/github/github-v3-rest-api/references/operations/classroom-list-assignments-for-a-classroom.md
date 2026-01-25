# GET /classrooms/{classroom_id}/assignments

**Resource:** [classroom](../resources/classroom.md)
**List assignments for a classroom**
**Operation ID:** `classroom/list-assignments-for-a-classroom`

Lists GitHub Classroom assignments for a classroom. Assignments will only be returned if the current user is an administrator of the GitHub Classroom.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [simple-classroom-assignment](../schemas/simple-classroom-assignment/simple-classroom-assignment.md)

