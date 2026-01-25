# issuing_transaction_fleet_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cardholder_prompt_data` | any | No | Answers to prompts presented to cardholder at point of sale. |
| `purchase_type` | string | No | The type of purchase. One of `fuel_purchase`, `non_fuel_purchase`, or `fuel_and_non_fuel_purchase`. |
| `reported_breakdown` | any | No | More information about the total amount. This information is not guaranteed to be accurate as some merchants may provide unreliable data. |
| `service_type` | string | No | The type of fuel service. One of `non_fuel_transaction`, `full_service`, or `self_service`. |

