# GET /rest/api/3/attachment/content/{id}

**Resource:** [Issue attachments](../resources/Issue-attachments.md)
**Get attachment content**
**Operation ID:** `getAttachmentContent`

Returns the contents of an attachment. A `Range` header can be set to define a range of bytes within the attachment to download. See the [HTTP Range header standard](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Range) for details.

To return a thumbnail of the attachment, use [Get attachment thumbnail](#api-rest-api-3-attachment-thumbnail-id-get).

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** For the issue containing the attachment:

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  If attachments are added in private comments, the comment-level restriction will be applied.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the attachment. |
| `redirect` | query | boolean | No | Whether a redirect is provided for the attachment download. Clients that do not automatically follow redirects can set this to `false` to avoid making multiple requests to download the attachment. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful when `redirect` is set to `false`. |
| 206 | Returned if the request is successful when a `Range` header is provided and `redirect` is set to `false`. |
| 303 | Returned if the request is successful. See the `Location` header for the download URL. |
| 400 | Returned if the range supplied in the `Range` header is malformed. |
| 401 | Returned if the authentication credentials are incorrect. |
| 403 | The user does not have the necessary permission. |
| 404 | Returned if:

 *  the attachment is not found.
 *  attachments are disabled in the Jira settings. |
| 416 | Returned if the server is unable to satisfy the range of bytes provided. |

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
