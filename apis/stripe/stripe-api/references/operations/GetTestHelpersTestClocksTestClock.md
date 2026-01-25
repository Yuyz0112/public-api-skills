# GET /v1/test_helpers/test_clocks/{test_clock}

**Resource:** [test_helpers](../resources/test-helpers.md)
**Retrieve a test clock**
**Operation ID:** `GetTestHelpersTestClocksTestClock`

<p>Retrieves a test clock.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `test_clock` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[test_helpers.test_clock](../schemas/test/test-helpers-test-clock.md)

