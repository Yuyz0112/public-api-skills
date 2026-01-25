# Tunnel Routing

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/teamnet/routes` | List tunnel routes | [View](../operations/tunnel-route-list-tunnel-routes.md) |
| POST | `/accounts/{account_id}/teamnet/routes` | Create a tunnel route | [View](../operations/tunnel-route-create-a-tunnel-route.md) |
| GET | `/accounts/{account_id}/teamnet/routes/ip/{ip}` | Get tunnel route by IP | [View](../operations/tunnel-route-get-tunnel-route-by-ip.md) |
| POST | `/accounts/{account_id}/teamnet/routes/network/{ip_network_encoded}` | Create a tunnel route (CIDR Endpoint) | [View](../operations/tunnel-route-create-a-tunnel-route-with-cidr.md) |
| DELETE | `/accounts/{account_id}/teamnet/routes/network/{ip_network_encoded}` | Delete a tunnel route (CIDR Endpoint) | [View](../operations/tunnel-route-delete-a-tunnel-route-with-cidr.md) |
| PATCH | `/accounts/{account_id}/teamnet/routes/network/{ip_network_encoded}` | Update a tunnel route (CIDR Endpoint) | [View](../operations/tunnel-route-update-a-tunnel-route-with-cidr.md) |
| GET | `/accounts/{account_id}/teamnet/routes/{route_id}` | Get tunnel route | [View](../operations/tunnel-route-get-tunnel-route.md) |
| DELETE | `/accounts/{account_id}/teamnet/routes/{route_id}` | Delete a tunnel route | [View](../operations/tunnel-route-delete-a-tunnel-route.md) |
| PATCH | `/accounts/{account_id}/teamnet/routes/{route_id}` | Update a tunnel route | [View](../operations/tunnel-route-update-a-tunnel-route.md) |
