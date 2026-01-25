# GET /rest/api/3/task/{taskId}

**Resource:** [Tasks](../resources/Tasks.md)
**Get task**
**Operation ID:** `getTask`

Returns the status of a [long-running asynchronous task](#async).

When a task has finished, this operation returns the JSON blob applicable to the task. See the documentation of the operation that created the task for details. Task details are not permanently retained. As of September 2019, details are retained for 14 days although this period may change without notice.

**Deprecation notice:** The required OAuth 2.0 scopes will be updated on June 15, 2024.

 *  `read:jira-work`

**[Permissions](#permissions) required:** either of:

 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).
 *  Creator of the task.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `taskId` | path | string | Yes | The ID of the task. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the task is not found. |

**Success Response Schema:**

[TaskProgressBeanObject](../schemas/Task/TaskProgressBeanObject.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
