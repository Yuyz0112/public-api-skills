# GET /group/member

**Resource:** [group](../resources/group.md)
**Operation ID:** `getUsersFromGroup`

This resource returns a <a href="#pagination">paginated</a> list of users who are members of the specified group and its subgroups.
 Users in the page are ordered by user names. User of this resource is required to have sysadmin or admin permissions.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `groupname` | query | string | No | a name of the group for which members will be returned. |
| `includeInactiveUsers` | query | boolean | No | inactive users will be included in the response if set to true. |
| `startAt` | query | integer (int64) | No | the index of the first user in group to return (0 based). |
| `maxResults` | query | integer (int32) | No | the maximum number of users to return (max 50). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

