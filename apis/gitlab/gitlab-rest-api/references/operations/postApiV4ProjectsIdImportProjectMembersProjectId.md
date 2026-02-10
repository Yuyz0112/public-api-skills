# POST /api/v4/projects/{id}/import_project_members/{project_id}

**Resource:** [Projects](../resources/Projects.md)
**Import members from another project**
**Operation ID:** `postApiV4ProjectsIdImportProjectMembersProjectId`

This feature was introduced in GitLab 14.2

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `project_id` | path | integer | Yes | The ID of the source project to import the members from. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden - Project |
| 404 | Project Not Found |
| 422 | Import failed |

