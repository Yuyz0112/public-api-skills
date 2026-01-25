# GET /assignments/{assignment_id}

**Resource:** [classroom](../resources/classroom.md)
**Get an assignment**
**Operation ID:** `classroom/get-an-assignment`

Gets a GitHub Classroom assignment. Assignment will only be returned if the current user is an administrator of the GitHub Classroom for the assignment.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[classroom-assignment](../schemas/classroom-assignment/classroom-assignment.md)

