# issuing_card_shipping

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address` | [address](address.md) | Yes |  |
| `address_validation` | any | No | Address validation details for the shipment. |
| `carrier` | enum: dhl, fedex, royal_mail... | No | The delivery company that shipped a card. |
| `customs` | any | No | Additional information that may be required for clearing customs. |
| `eta` | integer (unix-time) | No | A unix timestamp representing a best estimate of when the card will be delivered. |
| `name` | string | Yes | Recipient name. |
| `phone_number` | string | No | The phone number of the receiver of the shipment. Our courier partners will use this number to contact you in the event of card delivery issues. For individual shipments to the EU/UK, if this field is empty, we will provide them with the phone number provided when the cardholder was initially created. |
| `require_signature` | boolean | No | Whether a signature is required for card delivery. This feature is only supported for US users. Standard shipping service does not support signature on delivery. The default value for standard shipping service is false and for express and priority services is true. |
| `service` | enum: express, priority, standard | Yes | Shipment service, such as `standard` or `express`. |
| `status` | enum: canceled, delivered, failure... | No | The delivery status of the card. |
| `tracking_number` | string | No | A tracking number for a card shipment. |
| `tracking_url` | string | No | A link to the shipping carrier's site where you can view detailed information about a card shipment. |
| `type` | enum: bulk, individual | Yes | Packaging options. |

