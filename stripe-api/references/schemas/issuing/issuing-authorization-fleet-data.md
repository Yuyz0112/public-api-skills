# issuing_authorization_fleet_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cardholder_prompt_data` | any | No | Answers to prompts presented to the cardholder at the point of sale. Prompted fields vary depending on the configuration of your physical fleet cards. Typical points of sale support only numeric entry. |
| `purchase_type` | enum: fuel_and_non_fuel_purchase, fuel_purchase, non_fuel_purchase | No | The type of purchase. |
| `reported_breakdown` | any | No | More information about the total amount. Typically this information is received from the merchant after the authorization has been approved and the fuel dispensed. This information is not guaranteed to be accurate as some merchants may provide unreliable data. |
| `service_type` | enum: full_service, non_fuel_transaction, self_service | No | The type of fuel service. |

