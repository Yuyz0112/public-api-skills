# POST /projects/{project_gid}/addMembers

**Resource:** [Projects](../resources/Projects.md)
**Add users to a project**
**Operation ID:** `addMembersForProject`

Adds the specified list of users as members of the project. Note that a user being added as a member may also be added as a *follower* as a result of this operation. This is because the user's default notification settings (i.e., in the "Notifications" tab of "My Profile Settings") will override this endpoint's default behavior of setting "Tasks added" notifications to `false`.
Returns the updated project record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

Information about the members being added.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added members to the project. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
