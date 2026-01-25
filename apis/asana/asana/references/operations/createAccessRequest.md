# POST /access_requests

**Resource:** [Access requests](../resources/Access-requests.md)
**Create an access request**
**Operation ID:** `createAccessRequest`

Submits a new access request for a private object. Currently supports projects and portfolios.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created a new access request. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
