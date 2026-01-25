# GET /repos/{owner}/{repo}/readme/{dir}

**Resource:** [repos](../resources/repos.md)
**Get a repository README for a directory**
**Operation ID:** `repos/get-readme-in-directory`

Gets the README from a repository directory.

This endpoint supports the following custom media types. For more information, see "[Media types](https://docs.github.com/rest/using-the-rest-api/getting-started-with-the-rest-api#media-types)."

- **`application/vnd.github.raw+json`**: Returns the raw file contents. This is the default if you do not specify a media type.
- **`application/vnd.github.html+json`**: Returns the README in HTML. Markup languages are rendered to HTML using GitHub's open-source [Markup library](https://github.com/github/markup).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dir` | path | string | Yes | The alternate path to look for a README file |
| `ref` | query | string | No | The name of the commit/branch/tag. Default: the repository’s default branch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[content-file](../schemas/content-file/content-file.md)

