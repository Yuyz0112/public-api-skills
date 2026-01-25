# PUT /accounts/{account_id}/dex/devices/dex_tests/{dex_test_id}

**Resource:** [Device DEX Tests](../resources/Device-DEX-Tests.md)
**Update Device DEX test**
**Operation ID:** `device-dex-test-update-device-dex-test`

Update a DEX test.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes |  |
| `dex_test_id` | path | digital-experience-monitoring_uuid | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [digital-experience-monitoring_device-dex-test-schemas-http](../schemas/digital-experience-monitoring/digital-experience-monitoring-device-dex-test-schemas-http.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Dex test response |
| 4XX | Update Dex test response failure |

**Success Response Schema:**

[digital-experience-monitoring_dex-single_response](../schemas/digital-experience-monitoring/digital-experience-monitoring-dex-single-response.md)

## Security

- **api_email**
- **api_key**
