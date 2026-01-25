# PATCH /orgs/{org}/projectsV2/{project_number}/items/{item_id}

**Resource:** [projects](../resources/projects.md)
**Update project item for organization**
**Operation ID:** `projects/update-item-for-org`

Update a specific item in an organization-owned project.

## Request Body

Field updates to apply to the project item. Only text, number, date, single select, and iteration fields are supported.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[projects-v2-item-with-content](../schemas/projects-v2-item-with-content/projects-v2-item-with-content.md)

