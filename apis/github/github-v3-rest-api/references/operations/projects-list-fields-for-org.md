# GET /orgs/{org}/projectsV2/{project_number}/fields

**Resource:** [projects](../resources/projects.md)
**List project fields for organization**
**Operation ID:** `projects/list-fields-for-org`

List all fields for a specific organization-owned project.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [projects-v2-field](../schemas/projects-v2-field/projects-v2-field.md)

