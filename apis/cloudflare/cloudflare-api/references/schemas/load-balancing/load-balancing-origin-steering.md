# load-balancing_origin_steering

Configures origin steering for the pool. Controls how origins are selected for new sessions and traffic without session affinity.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `policy` | enum: random, hash, least_outstanding_requests... | No | The type of origin steering policy to use.
- `"random"`: Select an origin randomly.
- `"hash"`: Select an origin by computing a hash over the CF-Connecting-IP address.
- `"least_outstanding_requests"`: Select an origin by taking into consideration origin weights, as well as each origin's number of outstanding requests. Origins with more pending requests are weighted proportionately less relative to others.
- `"least_connections"`: Select an origin by taking into consideration origin weights, as well as each origin's number of open connections. Origins with more open connections are weighted proportionately less relative to others. Supported for HTTP/1 and HTTP/2 connections. |

