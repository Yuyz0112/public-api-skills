# POST /v1/test_helpers/test_clocks/{test_clock}/advance

**Resource:** [test_helpers](../resources/test-helpers.md)
**Advance a test clock**
**Operation ID:** `PostTestHelpersTestClocksTestClockAdvance`

<p>Starts advancing a test clock to a specified time in the future. Advancement is done when status changes to <code>Ready</code>.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `test_clock` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[test_helpers.test_clock](../schemas/test/test-helpers-test-clock.md)

