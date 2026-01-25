# PUT /rest/api/3/project-template/edit-template

**Resource:** [Project templates](../resources/Project-templates.md)
**Edit a custom project template**
**Operation ID:** `editTemplate`

Edit custom template

This API endpoint allows you to edit an existing customised template.

***Note: Custom Templates are only supported for Jira Enterprise edition.***

## Request Body

The object containing the updated template details: name, description

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [EditTemplateRequest](../schemas/Edit/EditTemplateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
