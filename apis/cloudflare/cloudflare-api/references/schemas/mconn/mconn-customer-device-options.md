# mconn_customer_device_options

Exactly one of id, serial_number, or provision_license must be provided.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `provision_license` | boolean | No | When true, create and provision a new licence key for the connector. |
| `serial_number` | string | No |  |

