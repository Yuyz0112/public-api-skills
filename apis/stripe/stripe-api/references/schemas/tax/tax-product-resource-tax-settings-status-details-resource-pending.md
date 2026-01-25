# tax_product_resource_tax_settings_status_details_resource_pending

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `missing_fields` | string[] | No | The list of missing fields that are required to perform calculations. It includes the entry `head_office` when the status is `pending`. It is recommended to set the optional values even if they aren't listed as required for calculating taxes. Calculations can fail if missing fields aren't explicitly provided on every call. |

