# GET /repos/{owner}/{repo}/tarball/{ref}

**Resource:** [repos](../resources/repos.md)
**Download a repository archive (tar)**
**Operation ID:** `repos/download-tarball-archive`

Gets a redirect URL to download a tar archive for a repository. If you omit `:ref`, the repository’s default branch (usually
`main`) will be used. Please make sure your HTTP framework is configured to follow redirects or you will need to use
the `Location` header to make a second `GET` request.

> [!NOTE]
> For private repositories, these links are temporary and expire after five minutes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ref` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 302 | Response |

