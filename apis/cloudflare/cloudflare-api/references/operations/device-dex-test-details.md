# GET /accounts/{account_id}/dex/devices/dex_tests

**Resource:** [Device DEX Tests](../resources/Device-DEX-Tests.md)
**List Device DEX tests**
**Operation ID:** `device-dex-test-details`

Fetch all DEX tests

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Device DEX test details response |
| 4XX | Device DEX test response failure |

**Success Response Schema:**

[digital-experience-monitoring_dex-response_collection](../schemas/digital-experience-monitoring/digital-experience-monitoring-dex-response-collection.md)

## Security

- **api_email**
- **api_key**
