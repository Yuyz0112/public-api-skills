# billing-premium-request-usage-report-org

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `timePeriod` | object | Yes |  |
| `organization` | string | Yes | The unique identifier of the organization. |
| `user` | string | No | The name of the user for the usage report. |
| `product` | string | No | The product for the usage report. |
| `model` | string | No | The model for the usage report. |
| `usageItems` | object[] | Yes |  |

## Nested Fields

### `timePeriod`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `year` | integer | Yes | The year for the usage report. |
| `month` | integer | No | The month for the usage report. |
| `day` | integer | No | The day for the usage report. |

### `usageItems`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `product` | string | Yes | Product name. |
| `sku` | string | Yes | SKU name. |
| `model` | string | Yes | Model name. |
| `unitType` | string | Yes | Unit type of the usage line item. |
| `pricePerUnit` | number | Yes | Price per unit of the usage line item. |
| `grossQuantity` | number | Yes | Gross quantity of the usage line item. |
| `grossAmount` | number | Yes | Gross amount of the usage line item. |
| `discountQuantity` | number | Yes | Discount quantity of the usage line item. |
| `discountAmount` | number | Yes | Discount amount of the usage line item. |
| `netQuantity` | number | Yes | Net quantity of the usage line item. |
| `netAmount` | number | Yes | Net amount of the usage line item. |

