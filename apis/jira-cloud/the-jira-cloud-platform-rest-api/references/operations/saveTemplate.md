# POST /rest/api/3/project-template/save-template

**Resource:** [Project templates](../resources/Project-templates.md)
**Save a custom project template**
**Operation ID:** `saveTemplate`

Save custom template

This API endpoint allows you to save a customised template

***Note: Custom Templates are only supported for Jira Enterprise edition.***

## Request Body

The object containing the template basic details: name, description

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SaveTemplateRequest](../schemas/Save/SaveTemplateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response |

**Success Response Schema:**

[SaveTemplateResponse](../schemas/Save/SaveTemplateResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
