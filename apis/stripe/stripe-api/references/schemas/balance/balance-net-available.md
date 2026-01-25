# balance_net_available

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Net balance amount, subtracting fees from platform-set pricing. |
| `destination` | string | Yes | ID of the external account for this net balance (not expandable). |
| `source_types` | [balance_amount_by_source_type](balance-amount-by-source-type.md) | No |  |

