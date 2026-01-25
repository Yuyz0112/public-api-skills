# POST /accounts/{account_id}/dex/devices/dex_tests

**Resource:** [Device DEX Tests](../resources/Device-DEX-Tests.md)
**Create Device DEX test**
**Operation ID:** `device-dex-test-create-device-dex-test`

Create a DEX test.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | digital-experience-monitoring_account_identifier | Yes |  |

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
