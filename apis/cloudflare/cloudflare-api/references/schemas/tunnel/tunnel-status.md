# tunnel_status

The status of the tunnel. Valid values are `inactive` (tunnel has never been run), `degraded` (tunnel is active and able to serve traffic but in an unhealthy state), `healthy` (tunnel is active and able to serve traffic), or `down` (tunnel can not serve traffic as it has no connections to the Cloudflare Edge).

**Type:** enum

## Values

- `inactive`
- `degraded`
- `healthy`
- `down`
