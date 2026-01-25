# GET /accounts/{account_id}/dlp/profiles/custom

**Resource:** [DLP Profiles](../resources/DLP-Profiles.md)
**List all custom profiles**
**Operation ID:** `dlp-profiles-list-all-custom-profiles`

Lists all DLP custom profiles in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List all custom profiles response. |
| 4XX | List all profiles failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**
