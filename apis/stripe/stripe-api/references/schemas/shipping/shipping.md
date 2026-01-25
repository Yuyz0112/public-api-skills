# shipping

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address` | [address](address.md) | No |  |
| `carrier` | string | No | The delivery service that shipped a physical product, such as Fedex, UPS, USPS, etc. |
| `name` | string | No | Recipient name. |
| `phone` | string | No | Recipient phone (including extension). |
| `tracking_number` | string | No | The tracking number for a physical product, obtained from the delivery service. If multiple tracking numbers were generated for this purchase, please separate them with commas. |

