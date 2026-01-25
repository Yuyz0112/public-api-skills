# POST /webhook_subscriptions/oauth_clients

**Resource:** [Webhooks](../resources/Webhooks.md)
**Create an OAuth client**
**Operation ID:** `createOauthClient`

Create a new OAuth client for webhook subscriptions. The client credentials will be validated by attempting to obtain an access token before creation.

Requires admin or owner role permissions.

Maximum of 10 OAuth clients per account.


## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateOAuthClientRequest](../schemas/Create/CreateOAuthClientRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | OAuth client created successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

