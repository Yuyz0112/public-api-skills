# PATCH /api/v4/projects/{id}/compliance_external_controls/{control_id}/status

**Resource:** [projects](../resources/projects.md)
**Update the status of a control**
**Operation ID:** `patchApiV4ProjectsIdComplianceExternalControlsControlIdStatus`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `control_id` | path | integer | Yes | The ID of the control |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

