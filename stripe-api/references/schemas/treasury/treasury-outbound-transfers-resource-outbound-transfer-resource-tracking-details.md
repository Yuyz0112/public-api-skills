# treasury_outbound_transfers_resource_outbound_transfer_resource_tracking_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ach` | [treasury_outbound_transfers_resource_ach_tracking_details](treasury-outbound-transfers-resource-ach-tracking-details.md) | No |  |
| `type` | enum: ach, us_domestic_wire | Yes | The US bank account network used to send funds. |
| `us_domestic_wire` | [treasury_outbound_transfers_resource_us_domestic_wire_tracking_details](treasury-outbound-transfers-resource-us-domestic-wire-tracking-details.md) | No |  |

