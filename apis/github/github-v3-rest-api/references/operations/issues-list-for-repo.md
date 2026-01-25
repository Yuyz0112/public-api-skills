# GET /repos/{owner}/{repo}/issues

**Resource:** [issues](../resources/issues.md)
**List repository issues**
**Operation ID:** `issues/list-for-repo`

List issues in a repository. Only open issues will be listed.

> [!NOTE]
> GitHub's REST API considers every pull request an issue, but not every issue is a pull request. For this reason, "Issues" endpoints may return both issues and pull requests in the response. You can identify pull requests by the `pull_request` key. Be aware that the `id` of a pull request returned from "Issues" endpoints will be an _issue id_. To find out the pull request id, use the "[List pull requests](https://docs.github.com/rest/pulls/pulls#list-pull-requests)" endpoint.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github.raw+json`**: Returns the raw markdown body. Response will include `body`. This is the default if you do not pass any specific media type.
- **`application/vnd.github.text+json`**: Returns a text only representation of the markdown body. Response will include `body_text`.
- **`application/vnd.github.html+json`**: Returns HTML rendered from the body's markdown. Response will include `body_html`.
- **`application/vnd.github.full+json`**: Returns raw, text, and HTML representations. Response will include `body`, `body_text`, and `body_html`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `milestone` | query | string | No | If an `integer` is passed, it should refer to a milestone by its `number` field. If the string `*` is passed, issues with any milestone are accepted. If the string `none` is passed, issues without milestones are returned. |
| `state` | query | enum: open, closed, all | No | Indicates the state of the issues to return. |
| `assignee` | query | string | No | Can be the name of a user. Pass in `none` for issues with no assigned user, and `*` for issues assigned to any user. |
| `type` | query | string | No | Can be the name of an issue type. If the string `*` is passed, issues with any type are accepted. If the string `none` is passed, issues without type are returned. |
| `creator` | query | string | No | The user that created the issue. |
| `mentioned` | query | string | No | A user that's mentioned in the issue. |
| `sort` | query | enum: created, updated, comments | No | What to sort results by. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 301 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [issue](../schemas/issue/issue.md)

