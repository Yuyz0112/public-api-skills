# GET /api/v4/projects/{id}/releases/{tag_name}/downloads/*direct_asset_path

**Resource:** [Releases](../resources/Releases.md)
**Download a project release asset file**
**Operation ID:** `getApiV4ProjectsIdReleasesTagNameDownloads*directAssetPath`

This feature was introduced in GitLab 15.4.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `tag_name` | path | string | Yes | The Git tag the release is associated with |
| `direct_asset_path` | query | string | Yes | The path to the file to download, as specified when creating the release asset |

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 404 | Not found |

