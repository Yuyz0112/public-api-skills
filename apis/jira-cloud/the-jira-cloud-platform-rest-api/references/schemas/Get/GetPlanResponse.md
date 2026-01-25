# GetPlanResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `crossProjectReleases` | GetCrossProjectReleaseResponse[] | No | The cross-project releases included in the plan. |
| `customFields` | GetCustomFieldResponse[] | No | The custom fields for the plan. |
| `exclusionRules` | any | No | The exclusion rules for the plan. |
| `id` | integer (int64) | Yes | The plan ID. |
| `issueSources` | GetIssueSourceResponse[] | No | The issue sources included in the plan. |
| `lastSaved` | string | No | The date when the plan was last saved in UTC. |
| `leadAccountId` | string | No | The account ID of the plan lead. |
| `name` | string | No | The plan name. |
| `permissions` | GetPermissionResponse[] | No | The permissions for the plan. |
| `scheduling` | any | Yes | The scheduling settings for the plan. |
| `status` | enum: Active, Trashed, Archived | Yes | The plan status. This is "Active", "Trashed" or "Archived". |

