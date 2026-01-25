# GET /users/{username}/projectsV2/{project_number}

**Resource:** [projects](../resources/projects.md)
**Get project for user**
**Operation ID:** `projects/get-for-user`

Get a specific user-owned project.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[projects-v2](../schemas/projects-v2/projects-v2.md)

