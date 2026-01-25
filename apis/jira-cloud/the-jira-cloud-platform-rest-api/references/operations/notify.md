# POST /rest/api/3/issue/{issueIdOrKey}/notify

**Resource:** [Issues](../resources/Issues.md)
**Send notification for issue**
**Operation ID:** `notify`

Creates an email notification for an issue and adds it to the mail queue.

**[Permissions](#permissions) required:**

 *  *Browse Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | ID or key of the issue that the notification is sent for. |

## Request Body

The request object for the notification and recipients.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [Notification](../schemas/Notification/Notification.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the email is queued for sending. |
| 400 | Returned if:

 *  the recipient is the same as the calling user.
 *  the recipient is invalid. For example, the recipient is set to the assignee, but the issue is unassigned.
 *  the issueIdOrKey is of an invalid/null issue.
 *  the request is invalid. For example, required fields are missing or have invalid values. |
| 403 | Returned if:

 *  outgoing emails are disabled.
 *  no SMTP server is configured. |
| 404 | Returned if the issue is not found. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
