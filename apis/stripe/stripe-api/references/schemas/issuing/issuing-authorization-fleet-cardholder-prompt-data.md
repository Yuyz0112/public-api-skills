# issuing_authorization_fleet_cardholder_prompt_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `alphanumeric_id` | string | No | [Deprecated] An alphanumeric ID, though typical point of sales only support numeric entry. The card program can be configured to prompt for a vehicle ID, driver ID, or generic ID. |
| `driver_id` | string | No | Driver ID. |
| `odometer` | integer | No | Odometer reading. |
| `unspecified_id` | string | No | An alphanumeric ID. This field is used when a vehicle ID, driver ID, or generic ID is entered by the cardholder, but the merchant or card network did not specify the prompt type. |
| `user_id` | string | No | User ID. |
| `vehicle_number` | string | No | Vehicle number. |

