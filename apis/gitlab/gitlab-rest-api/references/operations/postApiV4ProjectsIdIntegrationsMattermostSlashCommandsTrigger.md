# POST /api/v4/projects/{id}/integrations/mattermost_slash_commands/trigger

**Resource:** [Integrations](../resources/Integrations.md)
**Trigger a slash command for mattermost-slash-commands**
**Operation ID:** `postApiV4ProjectsIdIntegrationsMattermostSlashCommandsTrigger`

Added in GitLab 8.13

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 404 | Not found |

