# AssociateSecuritySchemeWithProjectDetails

Issue security scheme, project, and remapping details.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `oldToNewSecurityLevelMappings` | OldToNewSecurityLevelMappingsBean[] | No | The list of scheme levels which should be remapped to new levels of the issue security scheme. |
| `projectId` | string | Yes | The ID of the project. |
| `schemeId` | string | Yes | The ID of the issue security scheme. Providing null will clear the association with the issue security scheme. |

