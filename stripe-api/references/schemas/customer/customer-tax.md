# customer_tax

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `automatic_tax` | enum: failed, not_collecting, supported... | Yes | Surfaces if automatic tax computation is possible given the current customer location information. |
| `ip_address` | string | No | A recent IP address of the customer used for tax reporting and tax location inference. |
| `location` | any | No | The identified tax location of the customer. |
| `provider` | enum: anrok, avalara, sphere... | Yes | The tax calculation provider used for location resolution. Defaults to `stripe` when not using a [third-party provider](/tax/third-party-apps). |

