# DEX Synthetic Application Monitoring

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/dex/colos` | List Cloudflare colos | [View](../operations/dex-endpoints-list-colos.md) |
| GET | `/accounts/{account_id}/dex/devices/{device_id}/fleet-status/live` | Get the live status of a latest device | [View](../operations/devices-live-status.md) |
| GET | `/accounts/{account_id}/dex/fleet-status/devices` | List fleet status devices | [View](../operations/dex-fleet-status-devices.md) |
| GET | `/accounts/{account_id}/dex/fleet-status/live` | List fleet status details by dimension | [View](../operations/dex-fleet-status-live.md) |
| GET | `/accounts/{account_id}/dex/fleet-status/over-time` | List fleet status aggregate details by dimension | [View](../operations/dex-fleet-status-over-time.md) |
| GET | `/accounts/{account_id}/dex/http-tests/{test_id}` | Get details and aggregate metrics for an http test | [View](../operations/dex-endpoints-http-test-details.md) |
| GET | `/accounts/{account_id}/dex/http-tests/{test_id}/percentiles` | Get percentiles for an http test | [View](../operations/dex-endpoints-http-test-percentiles.md) |
| GET | `/accounts/{account_id}/dex/tests/overview` | List DEX test analytics | [View](../operations/dex-endpoints-list-tests-overview.md) |
| GET | `/accounts/{account_id}/dex/tests/unique-devices` | Get count of devices targeted | [View](../operations/dex-endpoints-tests-unique-devices.md) |
| GET | `/accounts/{account_id}/dex/traceroute-test-results/{test_result_id}/network-path` | Get details for a specific traceroute test run | [View](../operations/dex-endpoints-traceroute-test-result-network-path.md) |
| GET | `/accounts/{account_id}/dex/traceroute-tests/{test_id}` | Get details and aggregate metrics for a traceroute test | [View](../operations/dex-endpoints-traceroute-test-details.md) |
| GET | `/accounts/{account_id}/dex/traceroute-tests/{test_id}/network-path` | Get network path breakdown for a traceroute test | [View](../operations/dex-endpoints-traceroute-test-network-path.md) |
| GET | `/accounts/{account_id}/dex/traceroute-tests/{test_id}/percentiles` | Get percentiles for a traceroute test | [View](../operations/dex-endpoints-traceroute-test-percentiles.md) |
