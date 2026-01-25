# GET /users/{user_gid}/favorites

**Resource:** [Users](../resources/Users.md)
**Get a user's favorites**
**Operation ID:** `getFavoritesForUser`

<b>Required scope: </b><code>users:read</code>

Returns all of a user's favorites within a specified workspace and of a given type. The results are ordered exactly as they appear in the user's Asana sidebar in the web application. Note that this endpoint currently only returns favorites for the current user (i.e., the user associated with the authentication token).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the specified user's favorites. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: users:read
