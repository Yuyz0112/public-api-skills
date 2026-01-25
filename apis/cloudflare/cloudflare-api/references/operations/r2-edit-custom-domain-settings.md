# PUT /accounts/{account_id}/r2/buckets/{bucket_name}/domains/custom/{domain}

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Configure Custom Domain Settings**
**Operation ID:** `r2-edit-custom-domain-settings`

Edit the configuration for a custom domain on an existing R2 bucket.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2_account_identifier | Yes |  |
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `domain` | path | r2_domain_name | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [r2_edit_custom_domain_request](../schemas/r2/r2-edit-custom-domain-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit Custom Domain Configuration response. |
| 4XX | Edit Custom Domain Configuration response failure. |

## Security

- **api_token**
