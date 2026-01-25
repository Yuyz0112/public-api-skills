# PUT /webhook_subscriptions/oauth_clients/{id}

**Resource:** [Webhooks](../resources/Webhooks.md)
**Update an OAuth client**
**Operation ID:** `updateOauthClient`

Update an existing OAuth client. Any change will trigger token validation with the OAuth server.

Requires admin or owner role permissions.


## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateOAuthClientRequest](../schemas/Update/UpdateOAuthClientRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OAuth client updated successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

