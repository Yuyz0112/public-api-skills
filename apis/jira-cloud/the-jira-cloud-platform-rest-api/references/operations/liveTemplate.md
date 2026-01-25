# GET /rest/api/3/project-template/live-template

**Resource:** [Project templates](../resources/Project-templates.md)
**Gets a custom project template**
**Operation ID:** `liveTemplate`

Get custom template

This API endpoint allows you to get a live custom project template details by either templateKey or projectId

***Note: Custom Templates are only supported for Jira Enterprise edition.***

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectId` | query | string | No | optional - The \{@link String\} containing the project key linked to the custom template to retrieve |
| `templateKey` | query | string | No | optional - The \{@link String\} containing the key of the custom template to retrieve |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response |

**Success Response Schema:**

[ProjectTemplateModel](../schemas/Project/ProjectTemplateModel.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
