# DELETE /project/{projectIdOrKey}/role/{id}

**Resource:** [project](../resources/project.md)
**Operation ID:** `deleteActor`

Deletes actors (users or groups) from a project role.
 <p>
 <ul>
 <li>Delete a user from the role: <code>/rest/api/2/project/{projectIdOrKey}/role/{roleId}?user={username}</code></li>
 <li>Delete a group from the role: <code>/rest/api/2/project/{projectIdOrKey}/role/{roleId}?group={groupname}</code></li>
 </ul>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user` | query | string | No | the username of the user to remove from the project role |
| `group` | query | string | No | the groupname to remove from the project role |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

