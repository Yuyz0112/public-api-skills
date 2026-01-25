# GET /accounts/{account_id}/devices/posture

**Resource:** [Device posture rules](../resources/Device-posture-rules.md)
**List device posture rules**
**Operation ID:** `device-posture-rules-list-device-posture-rules`

Fetches device posture rules for a Zero Trust account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | teams-devices_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List device posture rules response. |
| 4XX | List device posture rules response failure. |

**Success Response Schema:**

[teams-devices_response_collection](../schemas/teams-devices/teams-devices-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
