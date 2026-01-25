# PUT /accounts/{account_id}/slurper/target/connectivity-precheck

**Resource:** [R2 Super Slurper](../resources/R2-Super-Slurper.md)
**Check target connectivity**
**Operation ID:** `slurper-check-target-connectivity`

Check whether tokens are valid against the target bucket

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [r2-slurper_R2TargetSchema](../schemas/r2-slurper/r2-slurper-R2TargetSchema.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Target connectivity checked |
| 4XX | Failure response |

## Security

- **api_email**
- **api_key**
- **api_token**
