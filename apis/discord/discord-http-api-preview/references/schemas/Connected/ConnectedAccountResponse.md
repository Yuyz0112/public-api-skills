# ConnectedAccountResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes |  |
| `name` | string,null | No |  |
| `type` | [ConnectedAccountProviders](ConnectedAccountProviders.md) | Yes |  |
| `friend_sync` | boolean | Yes |  |
| `integrations` | ConnectedAccountIntegrationResponse[] | No |  |
| `show_activity` | boolean | Yes |  |
| `two_way_link` | boolean | Yes |  |
| `verified` | boolean | Yes |  |
| `visibility` | [ConnectedAccountVisibility](ConnectedAccountVisibility.md) | Yes |  |
| `revoked` | boolean | No |  |

