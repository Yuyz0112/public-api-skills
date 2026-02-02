# GET /group

**Resource:** [group](../resources/group.md)
**Operation ID:** `getGroup`

Returns REST representation for the requested group. Allows to get list of active users belonging to the
 specified group and its subgroups if "users" expand option is provided. You can page through users list by using
 indexes in expand param. For example to get users from index 10 to index 15 use "users[10:15]" expand value. This
 will return 6 users (if there are at least 16 users in this group). Indexes are 0-based and inclusive.
 <p>
 This resource is deprecated, please use group/member API instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `groupname` | query | string | No | A name of requested group. |
| `expand` | query | string | No | List of fields to expand. Currently only available expand is "users". |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

