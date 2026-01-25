# magic-visibility-pcaps_pcaps_filter_v1

The packet capture filter. When this field is empty, all packets are captured.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `destination_address` | string | No | The destination IP address of the packet. |
| `destination_port` | number | No | The destination port of the packet. |
| `protocol` | number | No | The protocol number of the packet. |
| `source_address` | string | No | The source IP address of the packet. |
| `source_port` | number | No | The source port of the packet. |

