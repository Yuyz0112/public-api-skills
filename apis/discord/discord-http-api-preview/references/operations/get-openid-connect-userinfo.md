# GET /oauth2/userinfo

**Resource:** [oauth2](../resources/oauth2.md)
**Operation ID:** `get_openid_connect_userinfo`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_openid_connect_userinfo |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[OAuth2GetOpenIDConnectUserInfoResponse](../schemas/OAuth2GetOpenIDConnectUserInfoResponse/OAuth2GetOpenIDConnectUserInfoResponse.md)

## Security

- **BotToken**
- **OAuth2**: openid
