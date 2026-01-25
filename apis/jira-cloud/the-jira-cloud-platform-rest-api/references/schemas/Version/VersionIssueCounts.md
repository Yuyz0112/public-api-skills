# VersionIssueCounts

Various counts of issues within a version.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `customFieldUsage` | VersionUsageInCustomField[] | No | List of custom fields using the version. |
| `issueCountWithCustomFieldsShowingVersion` | integer (int64) | No | Count of issues where a version custom field is set to the version. |
| `issuesAffectedCount` | integer (int64) | No | Count of issues where the `affectedVersion` is set to the version. |
| `issuesFixedCount` | integer (int64) | No | Count of issues where the `fixVersion` is set to the version. |
| `self` | string (uri) | No | The URL of these count details. |

