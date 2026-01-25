# GET /repos/{owner}/{repo}/releases/tags/{tag}

**Resource:** [repos](../resources/repos.md)
**Get a release by tag name**
**Operation ID:** `repos/get-release-by-tag`

Get a published release with the specified tag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tag` | path | string | Yes | tag parameter |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[release](../schemas/release/release.md)

