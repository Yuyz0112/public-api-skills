# GET /classrooms

**Resource:** [classroom](../resources/classroom.md)
**List classrooms**
**Operation ID:** `classroom/list-classrooms`

Lists GitHub Classroom classrooms for the current user. Classrooms will only be returned if the current user is an administrator of one or more GitHub Classrooms.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [simple-classroom](../schemas/simple-classroom/simple-classroom.md)

