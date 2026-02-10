# PATCH /api/v4/jobs/{id}/trace

**Resource:** [Jobs](../resources/Jobs.md)
**Append a patch to the job trace**
**Operation ID:** `patchApiV4JobsIdTrace`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Job's ID |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | Trace was patched |
| 400 | Missing Content-Range header |
| 403 | Forbidden |
| 416 | Range not satisfiable |
| 429 | Too Many Requests |

