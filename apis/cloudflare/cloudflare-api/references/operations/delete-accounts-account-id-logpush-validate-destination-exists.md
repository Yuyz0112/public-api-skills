# POST /accounts/{account_id}/logpush/validate/destination/exists

**Resource:** [Logpush jobs for an account](../resources/Logpush-jobs-for-an-account.md)
**Check destination exists**
**Operation ID:** `delete-accounts-account_id-logpush-validate-destination-exists`

Checks if there is an existing job with a destination.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | logpush_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Check destination exists response. |
| 4XX | Check destination exists response failure. |

**Success Response Schema:**

[logpush_destination_exists_response](../schemas/logpush/logpush-destination-exists-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
