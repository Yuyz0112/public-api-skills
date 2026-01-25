# IssueSecurityLevelMember

Issue security level member.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `holder` | any | Yes | The user or group being granted the permission. It consists of a `type` and a type-dependent `parameter`. See [Holder object](../api-group-permission-schemes/#holder-object) in *Get all permission schemes* for more information. |
| `id` | integer (int64) | Yes | The ID of the issue security level member. |
| `issueSecurityLevelId` | integer (int64) | Yes | The ID of the issue security level. |

