# GET /accounts/{account_id}/dex/devices/dex_tests/{dex_test_id}

**Resource:** [Device DEX Tests](../resources/Device-DEX-Tests.md)
**Get Device DEX test**
**Operation ID:** `device-dex-test-get-device-dex-test`

Fetch a single DEX test.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes |  |
| `dex_test_id` | path | digital-experience-monitoring_schemas-test-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Device DEX test details response |
| 4XX | Device DEX test response failure |

**Success Response Schema:**

[digital-experience-monitoring_dex-single_response](../schemas/digital-experience-monitoring/digital-experience-monitoring-dex-single-response.md)

## Security

- **api_email**
- **api_key**
