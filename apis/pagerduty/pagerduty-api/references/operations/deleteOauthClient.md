# DELETE /webhook_subscriptions/oauth_clients/{id}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Delete an OAuth client**
**Operation ID:** `deleteOauthClient`

Delete an OAuth client. This will also remove the OAuth client association from any webhook subscriptions using it.

Requires admin or owner role permissions.


## Responses

| Status | Description |
|--------|-------------|
| 204 | OAuth client deleted successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

