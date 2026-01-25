# dispute_visa_compelling_evidence3_disputed_transaction

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `customer_account_id` | string | No | User Account ID used to log into business platform. Must be recognizable by the user. |
| `customer_device_fingerprint` | string | No | Unique identifier of the cardholder’s device derived from a combination of at least two hardware and software attributes. Must be at least 20 characters. |
| `customer_device_id` | string | No | Unique identifier of the cardholder’s device such as a device serial number (e.g., International Mobile Equipment Identity [IMEI]). Must be at least 15 characters. |
| `customer_email_address` | string | No | The email address of the customer. |
| `customer_purchase_ip` | string | No | The IP address that the customer used when making the purchase. |
| `merchandise_or_services` | enum: merchandise, services | No | Categorization of disputed payment. |
| `product_description` | string | No | A description of the product or service that was sold. |
| `shipping_address` | any | No | The address to which a physical product was shipped. All fields are required for Visa Compelling Evidence 3.0 evidence submission. |

