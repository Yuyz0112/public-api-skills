# GET /accounts/{account_id}/images/v1/stats

**Resource:** [Cloudflare Images](../resources/Cloudflare-Images.md)
**Images usage statistics**
**Operation ID:** `cloudflare-images-images-usage-statistics`

Fetch image statistics details for Cloudflare Images. The returned statistics detail storage usage, including the current image count vs this account's allowance.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | images_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Images usage statistics response |
| 4XX | Images usage statistics response failure |

**Success Response Schema:**

[images_images_stats_response](../schemas/images/images-images-stats-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
