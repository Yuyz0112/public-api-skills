# POST /accounts/{account_id}/dlp/patterns/validate

**Resource:** [DLP Settings](../resources/DLP-Settings.md)
**Validate a DLP regex pattern**
**Operation ID:** `dlp-pattern-validate`

Validates whether this pattern is a valid regular expression. Rejects it if
the regular expression is too complex or can match an unbounded-length
string. The regex will be rejected if it uses `*` or `+`. Bound the maximum
number of characters that can be matched using a range, e.g. `{1,100}`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Request Body

Validation query.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dlp_RegexValidationQuery](../schemas/dlp/dlp-RegexValidationQuery.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Validation response. |
| 4XX | Failed to validate. |

## Security

- **api_email**
- **api_key**
- **api_token**
