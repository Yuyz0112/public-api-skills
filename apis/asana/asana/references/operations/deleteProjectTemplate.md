# DELETE /project_templates/{project_template_gid}

**Resource:** [Project templates](../resources/Project-templates.md)
**Delete a project template**
**Operation ID:** `deleteProjectTemplate`

A specific, existing project template can be deleted by making a DELETE request on the URL for that project template.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified project template. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
