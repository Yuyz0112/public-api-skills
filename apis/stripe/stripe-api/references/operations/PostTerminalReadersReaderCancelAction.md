# POST /v1/terminal/readers/{reader}/cancel_action

**Resource:** [terminal](../resources/terminal.md)
**Cancel the current reader action**
**Operation ID:** `PostTerminalReadersReaderCancelAction`

<p>Cancels the current reader action. See <a href="/docs/terminal/payments/collect-card-payment?terminal-sdk-platform=server-driven#programmatic-cancellation">Programmatic Cancellation</a> for more details.</p>

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

