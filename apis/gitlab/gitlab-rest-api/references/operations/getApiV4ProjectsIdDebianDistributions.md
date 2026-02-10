# GET /api/v4/projects/{id}/debian_distributions

**Resource:** [Packages](../resources/Packages.md)
**Get a list of Debian Distributions**
**Operation ID:** `getApiV4ProjectsIdDebianDistributions`

This feature was introduced in 14.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `codename` | query | string | No | The Debian Codename |
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
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesPackagesDebianDistribution](../schemas/APIEntitiesPackagesDebianDistribution/APIEntitiesPackagesDebianDistribution.md)

