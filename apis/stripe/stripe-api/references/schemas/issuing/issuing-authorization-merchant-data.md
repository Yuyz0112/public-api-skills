# issuing_authorization_merchant_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `category` | string | Yes | A categorization of the seller's type of business. See our [merchant categories guide](https://docs.stripe.com/issuing/merchant-categories) for a list of possible values. |
| `category_code` | string | Yes | The merchant category code for the seller’s business |
| `city` | string | No | City where the seller is located |
| `country` | string | No | Country where the seller is located |
| `name` | string | No | Name of the seller |
| `network_id` | string | Yes | Identifier assigned to the seller by the card network. Different card networks may assign different network_id fields to the same merchant. |
| `postal_code` | string | No | Postal code where the seller is located |
| `state` | string | No | State where the seller is located |
| `tax_id` | string | No | The seller's tax identification number. Currently populated for French merchants only. |
| `terminal_id` | string | No | An ID assigned by the seller to the location of the sale. |
| `url` | string | No | URL provided by the merchant on a 3DS request |

