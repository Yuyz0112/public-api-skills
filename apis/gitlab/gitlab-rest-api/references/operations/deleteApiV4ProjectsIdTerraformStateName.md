# DELETE /api/v4/projects/{id}/terraform/state/{name}

**Resource:** [Terraform](../resources/Terraform.md)
**Delete a Terraform state of a certain name**
**Operation ID:** `deleteApiV4ProjectsIdTerraformStateName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name of a Terraform state |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |
| 422 | Validation failure |

