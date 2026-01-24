# issuing_transaction_flight_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `departure_at` | integer | No | The time that the flight departed. |
| `passenger_name` | string | No | The name of the passenger. |
| `refundable` | boolean | No | Whether the ticket is refundable. |
| `segments` | issuing_transaction_flight_data_leg[] | No | The legs of the trip. |
| `travel_agency` | string | No | The travel agency that issued the ticket. |

