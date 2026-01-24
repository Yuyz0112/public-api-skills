# POST /v1/test_helpers/terminal/readers/{reader}/timeout_input_collection

**Resource:** [test_helpers](../resources/test-helpers.md)
**Simulate an input collection timeout**
**Operation ID:** `PostTestHelpersTerminalReadersReaderTimeoutInputCollection`

<p>Use this endpoint to complete an input collection with a timeout error on a simulated reader.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `reader` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[terminal.reader](../schemas/terminal-reader/terminal-reader.md)

