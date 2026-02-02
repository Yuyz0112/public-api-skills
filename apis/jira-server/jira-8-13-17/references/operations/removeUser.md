# DELETE /user

**Resource:** [user](../resources/user.md)
**Operation ID:** `removeUser`

Removes user and its references (like project roles associations, watches, history).
 <br>
 <br>
 <b>Note:</b> user references will not be removed if multiple User Directories are used and there is a user with
 the same name existing in another directory (shadowing user).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | query | string | No | the username |
| `key` | query | string | No | user key |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

