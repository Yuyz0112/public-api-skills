# POST /orgs/{org}/projectsV2/{project_number}/drafts

**Resource:** [projects](../resources/projects.md)
**Create draft item for organization owned project**
**Operation ID:** `projects/create-draft-item-for-org`

Create draft issue item for the specified organization owned project.

## Request Body

Details of the draft item to create in the project.

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

