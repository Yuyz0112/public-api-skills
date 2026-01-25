# GET /rest/api/3/notificationscheme/project

**Resource:** [Issue notification schemes](../resources/Issue-notification-schemes.md)
**Get projects using notification schemes paginated**
**Operation ID:** `getNotificationSchemeToProjectMappings`

Returns a [paginated](#pagination) mapping of project that have notification scheme assigned. You can provide either one or multiple notification scheme IDs or project IDs to filter by. If you don't provide any, this will return a list of all mappings. Note that only company-managed (classic) projects are supported. This is because team-managed projects don't have a concept of a default notification scheme. The mappings are ordered by projectId.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | string | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | string | No | The maximum number of items to return per page. |
| `notificationSchemeId` | query | string[] | No | The list of notifications scheme IDs to be filtered out |
| `projectId` | query | string[] | No | The list of project IDs to be filtered out |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if search criteria are invalid, strings vs numbers for projectId, notificationSchemeId, startAt and maxResult |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[PageBeanNotificationSchemeAndProjectMappingJsonBean](../schemas/Page/PageBeanNotificationSchemeAndProjectMappingJsonBean.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
