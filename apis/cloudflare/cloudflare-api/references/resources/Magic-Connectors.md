# Magic Connectors

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/magic/connectors` | List Connectors | [View](../operations/mconn-connector-list.md) |
| POST | `/accounts/{account_id}/magic/connectors` | Add a connector to your account | [View](../operations/mconn-connector-create.md) |
| GET | `/accounts/{account_id}/magic/connectors/{connector_id}` | Fetch Connector | [View](../operations/mconn-connector-fetch.md) |
| PUT | `/accounts/{account_id}/magic/connectors/{connector_id}` | Replace Connector or Re-provision License Key | [View](../operations/mconn-connector-replace.md) |
| DELETE | `/accounts/{account_id}/magic/connectors/{connector_id}` | Remove a connector from your account | [View](../operations/mconn-connector-delete.md) |
| PATCH | `/accounts/{account_id}/magic/connectors/{connector_id}` | Edit Connector to update specific properties or Re-provision License Key | [View](../operations/mconn-connector-update.md) |
| GET | `/accounts/{account_id}/magic/connectors/{connector_id}/telemetry/events` | List Events | [View](../operations/mconn-connector-telemetry-events-list.md) |
| GET | `/accounts/{account_id}/magic/connectors/{connector_id}/telemetry/events/latest` | Get latest Events | [View](../operations/mconn-connector-telemetry-events-listLatest.md) |
| GET | `/accounts/{account_id}/magic/connectors/{connector_id}/telemetry/events/{event_t}.{event_n}` | Get Event | [View](../operations/mconn-connector-telemetry-events-get.md) |
| GET | `/accounts/{account_id}/magic/connectors/{connector_id}/telemetry/snapshots` | List Snapshots | [View](../operations/mconn-connector-telemetry-snapshots-list.md) |
| GET | `/accounts/{account_id}/magic/connectors/{connector_id}/telemetry/snapshots/latest` | Get latest Snapshots | [View](../operations/mconn-connector-telemetry-snapshots-listLatest.md) |
| GET | `/accounts/{account_id}/magic/connectors/{connector_id}/telemetry/snapshots/{snapshot_t}` | Get Snapshot | [View](../operations/mconn-connector-telemetry-snapshots-get.md) |
