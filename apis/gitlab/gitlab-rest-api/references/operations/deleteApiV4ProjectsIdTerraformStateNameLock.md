# DELETE /api/v4/projects/{id}/terraform/state/{name}/lock

**Resource:** [Terraform](../resources/Terraform.md)
**Unlock a Terraform state of a certain name**
**Operation ID:** `deleteApiV4ProjectsIdTerraformStateNameLock`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name of a Terraform state |
| `ID` | query | string | No | Terraform state lock ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |
| 409 | Conflict |
| 422 | Validation failure |

