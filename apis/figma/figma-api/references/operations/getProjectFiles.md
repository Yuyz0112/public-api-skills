# GET /v1/projects/{project_id}/files

**Resource:** [Projects](../resources/Projects.md)
**Get files in a project**
**Operation ID:** `getProjectFiles`

Get a list of all the Files within the specified project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project_id` | path | string | Yes | ID of the project to list files from |
| `branch_data` | query | boolean | No | Returns branch metadata in the response for each main file with a branch inside the project. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 403 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: projects:read, files:read
