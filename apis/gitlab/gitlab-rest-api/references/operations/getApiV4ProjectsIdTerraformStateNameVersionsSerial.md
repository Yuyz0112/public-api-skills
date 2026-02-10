# GET /api/v4/projects/{id}/terraform/state/{name}/versions/{serial}

**Resource:** [Terraform](../resources/Terraform.md)
**Get a Terraform state version**
**Operation ID:** `getApiV4ProjectsIdTerraformStateNameVersionsSerial`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `name` | path | string | Yes | The name of a Terraform state |
| `serial` | path | integer | Yes | The version number of the state |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |

