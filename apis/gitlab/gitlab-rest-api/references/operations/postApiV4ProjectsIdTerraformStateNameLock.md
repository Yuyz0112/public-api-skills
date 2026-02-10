# POST /api/v4/projects/{id}/terraform/state/{name}/lock

**Resource:** [Terraform](../resources/Terraform.md)
**Lock a Terraform state of a certain name**
**Operation ID:** `postApiV4ProjectsIdTerraformStateNameLock`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name of a Terraform state |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |
| 409 | Conflict |
| 422 | Validation failure |

