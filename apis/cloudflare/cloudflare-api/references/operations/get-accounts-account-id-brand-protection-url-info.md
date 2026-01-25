# GET /accounts/{account_id}/brand-protection/url-info

**Resource:** [brand_protection](../resources/brand-protection.md)
**Read submitted URLs by ID**
**Operation ID:** `get--accounts-{account_id}-brand-protection-url-info`

Return submitted URLs based on ID

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| default | (reference) |

**Success Response Schema:**

[brand-protection-api_URLInfo](../schemas/brand-protection-api/brand-protection-api-URLInfo.md)

## Security

- **api_token**
