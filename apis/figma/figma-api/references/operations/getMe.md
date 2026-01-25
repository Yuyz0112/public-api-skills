# GET /v1/me

**Resource:** [Users](../resources/Users.md)
**Get current user**
**Operation ID:** `getMe`

Returns the user information for the currently authenticated user.

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 403 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: current_user:read, files:read
