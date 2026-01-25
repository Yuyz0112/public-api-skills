# POST /projects/{project_gid}/addFollowers

**Resource:** [Projects](../resources/Projects.md)
**Add followers to a project**
**Operation ID:** `addFollowersForProject`

Adds the specified list of users as followers to the project. Followers are a subset of members who have opted in to receive "tasks added" notifications for a project. Therefore, if the users are not already members of the project, they will also become members as a result of this operation.
Returns the updated project record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

Information about the followers being added.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added followers to the project. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
