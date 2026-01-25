# PATCH /zones/{zone_id}/token_validation/rules/bulk

**Resource:** [Token Validation Token Rules](../resources/Token-Validation-Token-Rules.md)
**Bulk edit token validation rules**
**Operation ID:** `token-validation-rules-bulk-edit`

Edit token validation rules.

A request can update multiple Token Validation Rules.

Rules can be re-ordered using the `position` field.

Returns all updated rules.


## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 4XX | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
