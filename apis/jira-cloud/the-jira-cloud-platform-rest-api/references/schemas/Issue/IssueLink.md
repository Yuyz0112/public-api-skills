# IssueLink

Details of a link between issues.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The ID of the issue link. |
| `inwardIssue` | any | Yes | Provides details about the linked issue. If presenting this link in a user interface, use the `inward` field of the issue link type to label the link. |
| `outwardIssue` | any | Yes | Provides details about the linked issue. If presenting this link in a user interface, use the `outward` field of the issue link type to label the link. |
| `self` | string (uri) | No | The URL of the issue link. |
| `type` | any | Yes | The type of link between the issues. |

