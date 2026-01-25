# Comment

A comment.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author` | any | No | The ID of the user who created the comment. |
| `body` | any | No | The comment text in [Atlassian Document Format](https://developer.atlassian.com/cloud/jira/platform/apis/document/structure/). |
| `created` | string (date-time) | No | The date and time at which the comment was created. |
| `id` | string | No | The ID of the comment. |
| `jsdAuthorCanSeeRequest` | boolean | No | Whether the comment was added from an email sent by a person who is not part of the issue. See [Allow external emails to be added as comments on issues](https://support.atlassian.com/jira-service-management-cloud/docs/allow-external-emails-to-be-added-as-comments-on-issues/)for information on setting up this feature. |
| `jsdPublic` | boolean | No | Whether the comment is visible in Jira Service Desk. Defaults to true when comments are created in the Jira Cloud Platform. This includes when the site doesn't use Jira Service Desk or the project isn't a Jira Service Desk project and, therefore, there is no Jira Service Desk for the issue to be visible on. To create a comment with its visibility in Jira Service Desk set to false, use the Jira Service Desk REST API [Create request comment](https://developer.atlassian.com/cloud/jira/service-desk/rest/#api-rest-servicedeskapi-request-issueIdOrKey-comment-post) operation. |
| `properties` | EntityProperty[] | No | A list of comment properties. Optional on create and update. |
| `renderedBody` | string | No | The rendered version of the comment. |
| `self` | string | No | The URL of the comment. |
| `updateAuthor` | any | No | The ID of the user who updated the comment last. |
| `updated` | string (date-time) | No | The date and time at which the comment was updated last. |
| `visibility` | any | No | The group or role to which this comment is visible. Optional on create and update. |

