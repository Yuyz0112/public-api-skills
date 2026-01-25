# GET /rest/api/3/bulk/queue/{taskId}

**Resource:** [Issue bulk operations](../resources/Issue-bulk-operations.md)
**Get bulk issue operation progress**
**Operation ID:** `getBulkOperationProgress`

Use this to get the progress state for the specified bulk operation `taskId`.

**[Permissions](#permissions) required:**

 *  Global bulk change [permission](https://support.atlassian.com/jira-cloud-administration/docs/manage-global-permissions/).

If the task is running, this resource will return:

    {"taskId":"10779","status":"RUNNING","progressPercent":65,"submittedBy":{"accountId":"5b10a2844c20165700ede21g"},"created":1690180055963,"started":1690180056206,"updated":169018005829}

If the task has completed, then this resource will return:

    {"processedAccessibleIssues":[10001,10002],"created":1709189449954,"progressPercent":100,"started":1709189450154,"status":"COMPLETE","submittedBy":{"accountId":"5b10a2844c20165700ede21g"},"invalidOrInaccessibleIssueCount":0,"taskId":"10000","totalIssueCount":2,"updated":1709189450354}

**Note:** You can view task progress for up to 14 days from creation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `taskId` | path | string | Yes | The ID of the task. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[BulkOperationProgress](../schemas/Bulk/BulkOperationProgress.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
