# POST /rest/api/3/group

**Resource:** [Groups](../resources/Groups.md)
**Create group**
**Operation ID:** `createGroup`

Creates a group.

**[Permissions](#permissions) required:** Site administration (that is, member of the *site-admin* [group](https://confluence.atlassian.com/x/24xjL)).

## Request Body

The name of the group.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [AddGroupBean](../schemas/Add/AddGroupBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if group name is not specified or the group name is in use. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[Group](../schemas/Group/Group.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
