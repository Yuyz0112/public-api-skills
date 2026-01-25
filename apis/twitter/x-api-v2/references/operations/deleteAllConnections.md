# DELETE /2/connections/all

**Resource:** [Connections](../resources/Connections.md)
**Terminate all connections**
**Operation ID:** `deleteAllConnections`

Terminates all active streaming connections for the authenticated application.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[KillAllConnectionsResponse](../schemas/Kill/KillAllConnectionsResponse.md)

## Security

- **BearerToken**
