# GET /orgs/{org}/projectsV2/{project_number}/fields/{field_id}

**Resource:** [projects](../resources/projects.md)
**Get project field for organization**
**Operation ID:** `projects/get-field-for-org`

Get a specific field for an organization-owned project.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[projects-v2-field](../schemas/projects-v2-field/projects-v2-field.md)

