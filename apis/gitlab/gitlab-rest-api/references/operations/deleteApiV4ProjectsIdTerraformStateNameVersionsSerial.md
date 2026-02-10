# DELETE /api/v4/projects/{id}/terraform/state/{name}/versions/{serial}

**Resource:** [Terraform](../resources/Terraform.md)
**Delete a Terraform state version**
**Operation ID:** `deleteApiV4ProjectsIdTerraformStateNameVersionsSerial`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 403 | Forbidden |
| 404 | Not found |

