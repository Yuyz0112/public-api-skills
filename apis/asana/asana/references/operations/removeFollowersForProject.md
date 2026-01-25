# POST /projects/{project_gid}/removeFollowers

**Resource:** [Projects](../resources/Projects.md)
**Remove followers from a project**
**Operation ID:** `removeFollowersForProject`

Removes the specified list of users from following the project, this will not affect project membership status.
Returns the updated project record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

Information about the followers being removed.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully removed followers from the project. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
