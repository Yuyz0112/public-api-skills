# SaveProjectTemplateRequest

The request details to generate template from a project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `projectId` | integer (int64) | No | The ID of the target project |
| `templateGenerationOptions` | [CustomTemplateOptions](CustomTemplateOptions.md) | No |  |
| `templateType` | enum: LIVE, SNAPSHOT | No | The type of the template: LIVE | SNAPSHOT |

