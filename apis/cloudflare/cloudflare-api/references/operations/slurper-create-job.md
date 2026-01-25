# POST /accounts/{account_id}/slurper/jobs

**Resource:** [R2 Super Slurper](../resources/R2-Super-Slurper.md)
**Create a job**
**Operation ID:** `slurper-create-job`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [r2-slurper_CreateJobRequest](../schemas/r2-slurper/r2-slurper-CreateJobRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Job created |
| 409 | Maximum number of concurrent jobs has been reached |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
