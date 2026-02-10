# POST /api/v4/projects/{id}/terraform/state/{name}

**Resource:** [Terraform](../resources/Terraform.md)
**Add a new Terraform state or update an existing one**
**Operation ID:** `postApiV4ProjectsIdTerraformStateName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name of a Terraform state |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 204 | No data provided |
| 403 | Forbidden |
| 413 | Request Entity Too Large |
| 422 | Validation failure |

