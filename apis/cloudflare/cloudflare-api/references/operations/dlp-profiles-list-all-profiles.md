# GET /accounts/{account_id}/dlp/profiles

**Resource:** [DLP Profiles](../resources/DLP-Profiles.md)
**List all profiles**
**Operation ID:** `dlp-profiles-list-all-profiles`

Lists all DLP profiles in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `all` | query | boolean | No | Return all profiles, including those that current account does not have access to. |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List all profiles response. |
| 4XX | List all profiles failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
