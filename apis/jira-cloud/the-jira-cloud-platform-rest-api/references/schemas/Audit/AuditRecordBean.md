# AuditRecordBean

An audit record.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `associatedItems` | AssociatedItemBean[] | No | The list of items associated with the changed record. |
| `authorKey` | string | No | Deprecated, use `authorAccountId` instead. The key of the user who created the audit record. |
| `category` | string | No | The category of the audit record. For a list of these categories, see the help article [Auditing in Jira applications](https://confluence.atlassian.com/x/noXKM). |
| `changedValues` | ChangedValueBean[] | No | The list of values changed in the record event. |
| `created` | string (date-time) | No | The date and time on which the audit record was created. |
| `description` | string | No | The description of the audit record. |
| `eventSource` | string | No | The event the audit record originated from. |
| `id` | integer (int64) | No | The ID of the audit record. |
| `objectItem` | [AssociatedItemBean](AssociatedItemBean.md) | No |  |
| `remoteAddress` | string | No | The URL of the computer where the creation of the audit record was initiated. |
| `summary` | string | No | The summary of the audit record. |

