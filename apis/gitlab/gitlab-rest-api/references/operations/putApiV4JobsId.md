# PUT /api/v4/jobs/{id}

**Resource:** [Jobs](../resources/Jobs.md)
**Update a job**
**Operation ID:** `putApiV4JobsId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Job's ID |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Job was updated |
| 202 | Update accepted |
| 400 | Unknown parameters |
| 403 | Forbidden |
| 409 | Conflict |
| 429 | Too Many Requests |

