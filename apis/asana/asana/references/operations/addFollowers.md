# POST /goals/{goal_gid}/addFollowers

**Resource:** [Goals](../resources/Goals.md)
**Add a collaborator to a goal**
**Operation ID:** `addFollowers`

Adds followers to a goal. Returns the goal the followers were added to.
Each goal can be associated with zero or more followers in the system.
Requests to add/remove followers, if successful, will return the complete updated goal record, described above.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The followers to be added as collaborators

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added users as collaborators. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
