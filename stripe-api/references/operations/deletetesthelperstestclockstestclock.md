# DELETE /v1/test_helpers/test_clocks/{test_clock}

**Resource:** [test_helpers](../resources/test-helpers.md)
**Delete a test clock**
**Operation ID:** `DeleteTestHelpersTestClocksTestClock`

<p>Deletes a test clock.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `test_clock` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_test_helpers.test_clock](../schemas/deleted/deleted-test-helpers-test-clock.md)

