# DELETE /group/user

**Resource:** [group](../resources/group.md)
**Operation ID:** `removeUserFromGroup`

Removes given user from a group.
 <p>
 Returns no content

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `groupname` | query | string | No | A name of requested group. |
| `username` | query | string | No | User to remove from a group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

