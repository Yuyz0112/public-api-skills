# PUT /accounts/{account_id}/slurper/source/connectivity-precheck

**Resource:** [R2 Super Slurper](../resources/R2-Super-Slurper.md)
**Check source connectivity**
**Operation ID:** `slurper-check-source-connectivity`

Check whether tokens are valid against the source bucket

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [r2-slurper_SourceJobSchema](../schemas/r2-slurper/r2-slurper-SourceJobSchema.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Source connectivity checked |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
