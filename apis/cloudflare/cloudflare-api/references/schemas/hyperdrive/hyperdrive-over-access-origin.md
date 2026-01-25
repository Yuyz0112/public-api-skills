# hyperdrive_over-access-origin

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `access_client_id` | string | Yes | Defines the Client ID of the Access token to use when connecting to the origin database. |
| `access_client_secret` | string | Yes | Defines the Client Secret of the Access Token to use when connecting to the origin database. The API never returns this write-only value. |
| `host` | string | Yes | Defines the host (hostname or IP) of your origin database. |

