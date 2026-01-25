# ProjectPayload

The payload for creating a project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fieldLayoutSchemeId` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `issueSecuritySchemeId` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `issueTypeSchemeId` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `issueTypeScreenSchemeId` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `notificationSchemeId` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `permissionSchemeId` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `projectTypeKey` | enum: software, business, service_desk... | No | The [project type](https://confluence.atlassian.com/x/GwiiLQ#Jiraapplicationsoverview-Productfeaturesandprojecttypes), which defines the application-specific feature set. If you don't specify the project template you have to specify the project type. |
| `workflowSchemeId` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |

