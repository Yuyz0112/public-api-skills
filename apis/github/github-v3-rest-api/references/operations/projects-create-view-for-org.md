# POST /orgs/{org}/projectsV2/{project_number}/views

**Resource:** [projects](../resources/projects.md)
**Create a view for an organization-owned project**
**Operation ID:** `projects/create-view-for-org`

Create a new view in an organization-owned project. Views allow you to customize how items in a project are displayed and filtered.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response for creating a view in an organization-owned project. |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |
| 503 | Service unavailable |

**Success Response Schema:**

[projects-v2-view](../schemas/projects-v2-view/projects-v2-view.md)

