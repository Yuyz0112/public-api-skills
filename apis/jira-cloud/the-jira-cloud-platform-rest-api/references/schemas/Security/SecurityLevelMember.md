# SecurityLevelMember

Issue security level member.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `holder` | any | Yes | The user or group being granted the permission. It consists of a `type` and a type-dependent `parameter`. See [Holder object](../api-group-permission-schemes/#holder-object) in *Get all permission schemes* for more information. |
| `id` | string | Yes | The ID of the issue security level member. |
| `issueSecurityLevelId` | string | Yes | The ID of the issue security level. |
| `issueSecuritySchemeId` | string | Yes | The ID of the issue security scheme. |
| `managed` | boolean | No |  |

