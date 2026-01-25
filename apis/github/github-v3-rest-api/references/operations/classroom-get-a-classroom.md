# GET /classrooms/{classroom_id}

**Resource:** [classroom](../resources/classroom.md)
**Get a classroom**
**Operation ID:** `classroom/get-a-classroom`

Gets a GitHub Classroom classroom for the current user. Classroom will only be returned if the current user is an administrator of the GitHub Classroom.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[classroom](../schemas/classroom/classroom.md)

