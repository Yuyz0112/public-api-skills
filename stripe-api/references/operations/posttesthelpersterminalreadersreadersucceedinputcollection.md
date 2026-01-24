# POST /v1/test_helpers/terminal/readers/{reader}/succeed_input_collection

**Resource:** [test_helpers](../resources/test-helpers.md)
**Simulate a successful input collection**
**Operation ID:** `PostTestHelpersTerminalReadersReaderSucceedInputCollection`

<p>Use this endpoint to trigger a successful input collection on a simulated reader.</p>

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

