# zones_response_buffering

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | enum: response_buffering | No | Turn on or off whether Cloudflare should wait for an entire file
from the origin server before forwarding it to the site visitor. By
default, Cloudflare sends packets to the client as they arrive from
the origin server.
 |
| `value` | enum: on, off | No | The status of Response Buffering
 |

