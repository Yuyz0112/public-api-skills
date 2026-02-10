# GET /api/v4/projects/{id}/repository/changelog

**Resource:** [Repositories](../resources/Repositories.md)
**Generates a changelog section for a release and returns it**
**Operation ID:** `getApiV4ProjectsIdRepositoryChangelog`

This feature was introduced in GitLab 14.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `version` | query | string | Yes | The version of the release, using the semantic versioning format |
| `from` | query | string | No | The first commit in the range of commits to use for the changelog |
| `to` | query | string | No | The last commit in the range of commits to use for the changelog |
| `date` | query | string (date-time) | No | The date and time of the release |
| `trailer` | query | string | No | The Git trailer to use for determining if commits are to be included in the changelog |
| `config_file` | query | string | No | The file path to the configuration file as stored in the project's Git repository. Defaults to '.gitlab/changelog_config.yml' |
| `config_file_ref` | query | string | No | The git reference (for example, branch) where the changelog configuration file is defined. Defaults to the default repository branch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesChangelog](../schemas/APIEntitiesChangelog/APIEntitiesChangelog.md)

