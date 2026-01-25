# GET /webhook_subscriptions/oauth_clients

**Resource:** [Webhooks](../resources/Webhooks.md)
**List OAuth clients**
**Operation ID:** `listOauthClients`

List all OAuth clients for webhook subscriptions. Maximum of 10 clients per account.

Requires admin or owner role permissions.


## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of OAuth clients |
| 401 | (reference) |
| 403 | (reference) |

