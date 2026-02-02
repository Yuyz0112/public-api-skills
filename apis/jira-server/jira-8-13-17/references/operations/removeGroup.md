# DELETE /group

**Resource:** [group](../resources/group.md)
**Operation ID:** `removeGroup`

Deletes a group by given group parameter.
 <p>
 Returns no content

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `groupname` | query | string | No | (mandatory) The name of the group to delete. |
| `swapGroup` | query | string | No | If you delete a group and content is restricted to that group, the content will be hidden from all users.
 To prevent this, use this parameter to specify a different group to transfer the restrictions (comments and worklogs only) to. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

