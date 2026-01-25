# PUT /accounts/{account_id}/r2/buckets/{bucket_name}/domains/managed

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Update r2.dev Domain of Bucket**
**Operation ID:** `r2-put-bucket-public-policy`

Updates state of public access over the bucket's R2-managed (r2.dev) domain.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2_account_identifier | Yes |  |
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [r2_edit_managed_domain_request](../schemas/r2/r2-edit-managed-domain-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Managed Subdomain response. |
| 4XX | Update Managed Subdomain response failure. |

## Security

- **api_token**
