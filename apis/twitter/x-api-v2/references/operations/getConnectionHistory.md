# GET /2/connections

**Resource:** [Connections](../resources/Connections.md)
**Get Connection History**
**Operation ID:** `getConnectionHistory`

Returns active and historical streaming connections with disconnect reasons for the authenticated application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `status` | query | enum: active, inactive, all | No | Filter by connection status. Use 'active' for current connections, 'inactive' for historical/disconnected connections, or 'all' for both. |
| `endpoints` | query | string[] | No | Filter by streaming endpoint. Specify one or more endpoint names to filter results. |
| `max_results` | query | integer (int32) | No | The maximum number of results to return per page. |
| `pagination_token` | query | string | No | Token for paginating through results. Use the value from 'next_token' in the previous response. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2ConnectionsResponse](../schemas/Get/Get2ConnectionsResponse.md)

## Security

- **BearerToken**
