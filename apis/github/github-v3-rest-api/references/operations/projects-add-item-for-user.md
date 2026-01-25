# POST /users/{username}/projectsV2/{project_number}/items

**Resource:** [projects](../resources/projects.md)
**Add item to user owned project**
**Operation ID:** `projects/add-item-for-user`

Add an issue or pull request item to the specified user owned project.

## Request Body

Details of the item to add to the project. You can specify either the unique ID or the repository owner, name, and issue/PR number.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[projects-v2-item-simple](../schemas/projects-v2-item-simple/projects-v2-item-simple.md)

