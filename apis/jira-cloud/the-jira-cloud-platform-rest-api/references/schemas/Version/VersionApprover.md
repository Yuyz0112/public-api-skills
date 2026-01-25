# VersionApprover

Contains details about a version approver.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accountId` | string | No | The Atlassian account ID of the approver. |
| `declineReason` | string | No | A description of why the user is declining the approval. |
| `description` | string | No | A description of what the user is approving within the specified version. |
| `status` | string | No | The status of the approval, which can be *PENDING*, *APPROVED*, or *DECLINED* |

