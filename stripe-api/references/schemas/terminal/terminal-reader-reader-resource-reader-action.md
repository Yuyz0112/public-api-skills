# terminal_reader_reader_resource_reader_action

Represents an action performed by the reader

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `collect_inputs` | [terminal_reader_reader_resource_collect_inputs_action](terminal-reader-reader-resource-collect-inputs-action.md) | No |  |
| `collect_payment_method` | [terminal_reader_reader_resource_collect_payment_method_action](terminal-reader-reader-resource-collect-payment-method-action.md) | No |  |
| `confirm_payment_intent` | [terminal_reader_reader_resource_confirm_payment_intent_action](terminal-reader-reader-resource-confirm-payment-intent-action.md) | No |  |
| `failure_code` | string | No | Failure code, only set if status is `failed`. |
| `failure_message` | string | No | Detailed failure message, only set if status is `failed`. |
| `process_payment_intent` | [terminal_reader_reader_resource_process_payment_intent_action](terminal-reader-reader-resource-process-payment-intent-action.md) | No |  |
| `process_setup_intent` | [terminal_reader_reader_resource_process_setup_intent_action](terminal-reader-reader-resource-process-setup-intent-action.md) | No |  |
| `refund_payment` | [terminal_reader_reader_resource_refund_payment_action](terminal-reader-reader-resource-refund-payment-action.md) | No |  |
| `set_reader_display` | [terminal_reader_reader_resource_set_reader_display_action](terminal-reader-reader-resource-set-reader-display-action.md) | No |  |
| `status` | enum: failed, in_progress, succeeded | Yes | Status of the action performed by the reader. |
| `type` | enum: collect_inputs, collect_payment_method, confirm_payment_intent... | Yes | Type of action performed by the reader. |

