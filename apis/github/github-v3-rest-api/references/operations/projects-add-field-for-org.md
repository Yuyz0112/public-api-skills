# POST /orgs/{org}/projectsV2/{project_number}/fields

**Resource:** [projects](../resources/projects.md)
**Add a field to an organization-owned project.**
**Operation ID:** `projects/add-field-for-org`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response for adding a field to an organization-owned project. |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[projects-v2-field](../schemas/projects-v2-field/projects-v2-field.md)

