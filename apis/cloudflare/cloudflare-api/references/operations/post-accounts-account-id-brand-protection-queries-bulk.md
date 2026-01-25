# POST /accounts/{account_id}/brand-protection/queries/bulk

**Resource:** [domain_search](../resources/domain-search.md)
**Create new saved string queries in bulk**
**Operation ID:** `post--accounts-{account_id}-brand-protection-queries-bulk`

Return a success message after creating new saved string queries in bulk

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [brand-protection-api_QueryBulk](../schemas/brand-protection-api/brand-protection-api-QueryBulk.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 422 | (reference) |
| default | (reference) |

## Security

- **api_token**
