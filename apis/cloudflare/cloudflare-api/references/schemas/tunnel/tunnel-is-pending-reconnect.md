# tunnel_is_pending_reconnect

Cloudflare continues to track connections for several minutes after they disconnect. This is an optimization to improve latency and reliability of reconnecting.  If `true`, the connection has disconnected but is still being tracked. If `false`, the connection is actively serving traffic.

**Type:** primitive

