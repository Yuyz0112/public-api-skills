# DELETE /rest/api/3/project-template/remove-template

**Resource:** [Project templates](../resources/Project-templates.md)
**Deletes a custom project template**
**Operation ID:** `removeTemplate`

Remove custom template

This API endpoint allows you to remove a specified customised template

***Note: Custom Templates are only supported for Jira Enterprise edition.***

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `templateKey` | query | string | Yes | The \{@link String\} containing the key of the custom template to remove |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
