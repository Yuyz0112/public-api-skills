# PUT /issue/{issueIdOrKey}/assignee

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `assign`

Assigns an issue to a user.
 You can use this resource to assign issues when the user submitting the request has the assign permission but not the
 edit issue permission.
 If the name is "-1" automatic assignee is used.  A null name will remove the assignee.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

