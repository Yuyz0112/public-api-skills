# PATCH /accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_protection_status

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Update protection status.**
**Operation ID:** `updateProtectionStatus`

Update the protection status of the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The account ID. |

## Request Body

The update to apply to the protection status.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dos_UpdateProtectionStatus](../schemas/dos/dos-UpdateProtectionStatus.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update protection status response. |
| 4XX | Update protection status failure. |

**Success Response Schema:**

[dos_protection-status-response](../schemas/dos/dos-protection-status-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
