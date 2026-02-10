# POST /api/v4/projects/{id}/terraform/state/{name}/authorize

**Resource:** [Terraform](../resources/Terraform.md)
**Authorize Terraform state upload**
**Operation ID:** `postApiV4ProjectsIdTerraformStateNameAuthorize`

This feature was introduced in GitLab 18.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name of a Terraform state |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

