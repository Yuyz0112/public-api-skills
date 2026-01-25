# DELETE /accounts/{account_id}/dex/devices/dex_tests/{dex_test_id}

**Resource:** [Device DEX Tests](../resources/Device-DEX-Tests.md)
**Delete Device DEX test**
**Operation ID:** `device-dex-test-delete-device-dex-test`

Delete a Device DEX test. Returns the remaining device dex tests for the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes |  |
| `dex_test_id` | path | digital-experience-monitoring_uuid | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Device DEX test response |
| 4XX | Delete DEX test response failure |

**Success Response Schema:**

[digital-experience-monitoring_dex-delete-response-collection](../schemas/digital-experience-monitoring/digital-experience-monitoring-dex-delete-response-collection.md)

## Security

- **api_email**
- **api_key**
