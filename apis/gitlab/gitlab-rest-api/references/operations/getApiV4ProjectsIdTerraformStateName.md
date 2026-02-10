# GET /api/v4/projects/{id}/terraform/state/{name}

**Resource:** [Terraform](../resources/Terraform.md)
**Get a Terraform state by its name**
**Operation ID:** `getApiV4ProjectsIdTerraformStateName`

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
| 204 | Empty state |
| 403 | Forbidden |
| 404 | Not found |
| 422 | Validation failure |

