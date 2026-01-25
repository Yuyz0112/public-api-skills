# POST /goals/{goal_gid}/removeFollowers

**Resource:** [Goals](../resources/Goals.md)
**Remove a collaborator from a goal**
**Operation ID:** `removeFollowers`

Removes followers from a goal. Returns the goal the followers were removed from.
Each goal can be associated with zero or more followers in the system.
Requests to add/remove followers, if successful, will return the complete updated goal record, described above.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The followers to be removed as collaborators

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully removed users as collaborators. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
