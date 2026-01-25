# mconn_snapshot_netdev

Snapshot Netdev

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `connector_id` | string | No | Connector identifier |
| `name` | string | Yes | Name of the network device |
| `recv_bytes` | number | Yes | Total bytes received |
| `recv_compressed` | number | Yes | Compressed packets received |
| `recv_drop` | number | Yes | Packets dropped |
| `recv_errs` | number | Yes | Bad packets received |
| `recv_fifo` | number | Yes | FIFO overruns |
| `recv_frame` | number | Yes | Frame alignment errors |
| `recv_multicast` | number | Yes | Multicast packets received |
| `recv_packets` | number | Yes | Total packets received |
| `sent_bytes` | number | Yes | Total bytes transmitted |
| `sent_carrier` | number | Yes | Number of packets not sent due to carrier errors |
| `sent_colls` | number | Yes | Number of collisions |
| `sent_compressed` | number | Yes | Number of compressed packets transmitted |
| `sent_drop` | number | Yes | Number of packets dropped during transmission |
| `sent_errs` | number | Yes | Number of transmission errors |
| `sent_fifo` | number | Yes | FIFO overruns |
| `sent_packets` | number | Yes | Total packets transmitted |

