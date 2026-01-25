# Templates

Templates is a new feature which will allow customers to create message templates to be leveraged by (but not limited to) status updates. The API will be secured to customers with the status updates entitlements.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/templates` | List templates | [View](../operations/getTemplates.md) |
| POST | `/templates` | Create a template | [View](../operations/createTemplate.md) |
| GET | `/templates/{id}` | Get a template | [View](../operations/getTemplate.md) |
| PUT | `/templates/{id}` | Update a template | [View](../operations/updateTemplate.md) |
| DELETE | `/templates/{id}` | Delete a template | [View](../operations/deleteTemplate.md) |
| POST | `/templates/{id}/render` | Render a template | [View](../operations/renderTemplate.md) |
| GET | `/templates/fields` | List template fields | [View](../operations/getTemplateFields.md) |
