# billing-usage-report

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `usageItems` | object[] | No |  |

## Nested Fields

### `usageItems`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string | Yes | Date of the usage line item. |
| `product` | string | Yes | Product name. |
| `sku` | string | Yes | SKU name. |
| `quantity` | integer | Yes | Quantity of the usage line item. |
| `unitType` | string | Yes | Unit type of the usage line item. |
| `pricePerUnit` | number | Yes | Price per unit of the usage line item. |
| `grossAmount` | number | Yes | Gross amount of the usage line item. |
| `discountAmount` | number | Yes | Discount amount of the usage line item. |
| `netAmount` | number | Yes | Net amount of the usage line item. |
| `organizationName` | string | Yes | Name of the organization. |
| `repositoryName` | string | No | Name of the repository. |

