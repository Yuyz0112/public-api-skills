# POST /api/v4/integrations/jira_connect/subscriptions

**Resource:** [Jira connect subscriptions](../resources/Jira-connect-subscriptions.md)
**Subscribe a namespace to a JiraConnectInstallation**
**Operation ID:** `postApiV4IntegrationsJiraConnectSubscriptions`

Subscribes the namespace to the JiraConnectInstallation

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesBasicSuccess](../schemas/APIEntitiesBasicSuccess/APIEntitiesBasicSuccess.md)

