# POST /v1/test_helpers/test_clocks

**Resource:** [test_helpers](../resources/test-helpers.md)
**Create a test clock**
**Operation ID:** `PostTestHelpersTestClocks`

<p>Creates a new test clock that can be attached to new customers and quotes.</p>

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

