# POST /accounts/{account_id}/r2/temp-access-credentials

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Create Temporary Access Credentials**
**Operation ID:** `r2-create-temp-access-credentials`

Creates temporary access credentials on a bucket that can be optionally scoped to prefixes or objects.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [r2_temp_access_creds_request](../schemas/r2/r2-temp-access-creds-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create temporary access credentials response. |
| 4XX | Create temporary access credentials response failure. |

## Security

- **api_token**
