# DELETE /api/v4/projects/{id}/debian_distributions/{codename}

**Resource:** [Packages](../resources/Packages.md)
**Delete a Debian Distribution**
**Operation ID:** `deleteApiV4ProjectsIdDebianDistributionsCodename`

This feature was introduced in 14.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `codename` | path | string | Yes | The Debian Codename |
| `suite` | query | string | No | The Debian Suite |
| `origin` | query | string | No | The Debian Origin |
| `label` | query | string | No | The Debian Label |
| `version` | query | string | No | The Debian Version |
| `description` | query | string | No | The Debian Description |
| `valid_time_duration_seconds` | query | integer | No | The duration before the Release file should be considered expired by the client |
| `components` | query | any | No | The list of Components |
| `architectures` | query | any | No | The list of Architectures |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

