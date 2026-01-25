# CreatePlanRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `crossProjectReleases` | CreateCrossProjectReleaseRequest[] | No | The cross-project releases to include in the plan. |
| `customFields` | CreateCustomFieldRequest[] | No | The custom fields for the plan. |
| `exclusionRules` | any | No | The exclusion rules for the plan. |
| `issueSources` | CreateIssueSourceRequest[] | Yes | The issue sources to include in the plan. |
| `leadAccountId` | string | No | The account ID of the plan lead. |
| `name` | string | Yes | The plan name. |
| `permissions` | CreatePermissionRequest[] | No | The permissions for the plan. |
| `scheduling` | any | Yes | The scheduling settings for the plan. |

