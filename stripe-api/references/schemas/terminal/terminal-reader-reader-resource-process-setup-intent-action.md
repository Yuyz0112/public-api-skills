# terminal_reader_reader_resource_process_setup_intent_action

Represents a reader action to process a setup intent

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `generated_card` | string | No | ID of a card PaymentMethod generated from the card_present PaymentMethod that may be attached to a Customer for future transactions. Only present if it was possible to generate a card PaymentMethod. |
| `process_config` | [terminal_reader_reader_resource_process_setup_config](terminal-reader-reader-resource-process-setup-config.md) | No |  |
| `setup_intent` | any | Yes | Most recent SetupIntent processed by the reader. |

