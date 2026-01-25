# terminal_reader_reader_resource_process_config

Represents a per-transaction override of a reader configuration

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enable_customer_cancellation` | boolean | No | Enable customer-initiated cancellation when processing this payment. |
| `return_url` | string | No | If the customer doesn't abandon authenticating the payment, they're redirected to this URL after completion. |
| `skip_tipping` | boolean | No | Override showing a tipping selection screen on this transaction. |
| `tipping` | [terminal_reader_reader_resource_tipping_config](terminal-reader-reader-resource-tipping-config.md) | No |  |

