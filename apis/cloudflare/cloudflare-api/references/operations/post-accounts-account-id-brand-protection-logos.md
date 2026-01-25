# POST /accounts/{account_id}/brand-protection/logos

**Resource:** [logo_match](../resources/logo-match.md)
**Create new saved logo queries from image files**
**Operation ID:** `post--accounts-{account_id}-brand-protection-logos`

Return new saved logo queries created from image files

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tag` | query | string | No |  |
| `match_type` | query | string | No |  |
| `threshold` | query | number | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

**Schema:** [brand-protection-api_ImageFile](../schemas/brand-protection-api/brand-protection-api-ImageFile.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 422 | (reference) |
| default | (reference) |

**Success Response Schema:**

[brand-protection-api_Logo](../schemas/brand-protection-api/brand-protection-api-Logo.md)

## Security

- **api_token**
