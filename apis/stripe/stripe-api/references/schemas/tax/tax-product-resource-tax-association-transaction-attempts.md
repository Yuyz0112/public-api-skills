# tax_product_resource_tax_association_transaction_attempts

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `committed` | [tax_product_resource_tax_association_transaction_attempts_resource_committed](tax-product-resource-tax-association-transaction-attempts-resource-committed.md) | No |  |
| `errored` | [tax_product_resource_tax_association_transaction_attempts_resource_errored](tax-product-resource-tax-association-transaction-attempts-resource-errored.md) | No |  |
| `source` | string | Yes | The source of the tax transaction attempt. This is either a refund or a payment intent. |
| `status` | string | Yes | The status of the transaction attempt. This can be `errored` or `committed`. |

