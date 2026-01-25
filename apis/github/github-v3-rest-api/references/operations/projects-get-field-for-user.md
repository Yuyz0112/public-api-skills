# GET /users/{username}/projectsV2/{project_number}/fields/{field_id}

**Resource:** [projects](../resources/projects.md)
**Get project field for user**
**Operation ID:** `projects/get-field-for-user`

Get a specific field for a user-owned project.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[projects-v2-field](../schemas/projects-v2-field/projects-v2-field.md)

