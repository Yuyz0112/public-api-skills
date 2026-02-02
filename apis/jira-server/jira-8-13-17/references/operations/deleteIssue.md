# DELETE /issue/{issueIdOrKey}

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `deleteIssue`

Delete an issue.
 <p/>
 If the issue has subtasks you must set the parameter deleteSubtasks=true to delete the issue.
 You cannot delete an issue without its subtasks also being deleted.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `deleteSubtasks` | query | string | No | a String of true or false indicating that any subtasks should also be deleted.  If the
                       issue has no subtasks this parameter is ignored.  If the issue has subtasks and this parameter is missing or false,
                       then the issue will not be deleted and an error will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

