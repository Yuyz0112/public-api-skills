# DELETE /accounts/{account_id}/brand-protection/queries

**Resource:** [domain_search](../resources/domain-search.md)
**Delete saved string queries by ID**
**Operation ID:** `delete--accounts-{account_id}-brand-protection-queries`

Return a success message after deleting saved string queries by ID

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | query | string | No |  |
| `tag` | query | string | No |  |
| `scan` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 422 | (reference) |
| default | (reference) |

## Security

- **api_token**
