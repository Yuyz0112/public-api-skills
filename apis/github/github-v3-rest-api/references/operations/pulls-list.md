# GET /repos/{owner}/{repo}/pulls

**Resource:** [pulls](../resources/pulls.md)
**List pull requests**
**Operation ID:** `pulls/list`

Lists pull requests in a specified repository.

Draft pull requests are available in public repositories with GitHub
Free and GitHub Free for organizations, GitHub Pro, and legacy per-repository billing
plans, and in public and private repositories with GitHub Team and GitHub Enterprise
Cloud. For more information, see [GitHub's products](https://docs.github.com/github/getting-started-with-github/githubs-products)
in the GitHub Help documentation.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github.raw+json`**: Returns the raw markdown body. Response will include `body`. This is the default if you do not pass any specific media type.
- **`application/vnd.github.text+json`**: Returns a text only representation of the markdown body. Response will include `body_text`.
- **`application/vnd.github.html+json`**: Returns HTML rendered from the body's markdown. Response will include `body_html`.
- **`application/vnd.github.full+json`**: Returns raw, text, and HTML representations. Response will include `body`, `body_text`, and `body_html`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `state` | query | enum: open, closed, all | No | Either `open`, `closed`, or `all` to filter by state. |
| `head` | query | string | No | Filter pulls by head user or head organization and branch name in the format of `user:ref-name` or `organization:ref-name`. For example: `github:new-script-format` or `octocat:test-branch`. |
| `base` | query | string | No | Filter pulls by base branch name. Example: `gh-pages`. |
| `sort` | query | enum: created, updated, popularity... | No | What to sort results by. `popularity` will sort by the number of comments. `long-running` will sort by date created and will limit the results to pull requests that have been open for more than a month and have had activity within the past month. |
| `direction` | query | enum: asc, desc | No | The direction of the sort. Default: `desc` when sort is `created` or sort is not specified, otherwise `asc`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [pull-request-simple](../schemas/pull-request-simple/pull-request-simple.md)

