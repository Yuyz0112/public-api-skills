# POST /accounts/{account_id}/r2/buckets/{bucket_name}/domains/custom

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Attach Custom Domain To Bucket**
**Operation ID:** `r2-add-custom-domain`

Register a new custom domain for an existing R2 bucket.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2_account_identifier | Yes |  |
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [r2_add_custom_domain_request](../schemas/r2/r2-add-custom-domain-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Add Custom Domain response. |
| 4XX | Add Custom Domain response failure. |

## Security

- **api_token**
