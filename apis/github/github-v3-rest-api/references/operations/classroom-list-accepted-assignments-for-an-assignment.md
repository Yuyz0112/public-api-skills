# GET /assignments/{assignment_id}/accepted_assignments

**Resource:** [classroom](../resources/classroom.md)
**List accepted assignments for an assignment**
**Operation ID:** `classroom/list-accepted-assignments-for-an-assignment`

Lists any assignment repositories that have been created by students accepting a GitHub Classroom assignment. Accepted assignments will only be returned if the current user is an administrator of the GitHub Classroom for the assignment.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [classroom-accepted-assignment](../schemas/classroom-accepted-assignment/classroom-accepted-assignment.md)

