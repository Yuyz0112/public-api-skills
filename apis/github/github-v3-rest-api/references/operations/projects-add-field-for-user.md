# POST /users/{username}/projectsV2/{project_number}/fields

**Resource:** [projects](../resources/projects.md)
**Add field to user owned project**
**Operation ID:** `projects/add-field-for-user`

Add a field to a specified user owned project.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[projects-v2-field](../schemas/projects-v2-field/projects-v2-field.md)

