# GET /repos/{owner}/{repo}/zipball/{ref}

**Resource:** [repos](../resources/repos.md)
**Download a repository archive (zip)**
**Operation ID:** `repos/download-zipball-archive`

Gets a redirect URL to download a zip archive for a repository. If you omit `:ref`, the repository’s default branch (usually
`main`) will be used. Please make sure your HTTP framework is configured to follow redirects or you will need to use
the `Location` header to make a second `GET` request.

> [!NOTE]
> For private repositories, these links are temporary and expire after five minutes. If the repository is empty, you will receive a 404 when you follow the redirect.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ref` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 302 | Response |

