# POST /accounts/{account_id}/brand-protection/queries

**Resource:** [domain_search](../resources/domain-search.md)
**Create new saved string queries**
**Operation ID:** `post--accounts-{account_id}-brand-protection-queries`

Return a success message after creating new saved string queries

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | query | string | No |  |
| `tag` | query | string | No |  |
| `scan` | query | boolean | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [brand-protection-api_Query](../schemas/brand-protection-api/brand-protection-api-Query.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 422 | (reference) |
| default | (reference) |

## Security

- **api_token**
