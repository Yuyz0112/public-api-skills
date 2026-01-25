# CreateComplianceJobRequest

A request to create a new batch compliance job.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | [ComplianceJobName](ComplianceJobName.md) | No |  |
| `resumable` | boolean | No | If true, this endpoint will return a pre-signed URL with resumable uploads enabled. |
| `type` | enum: tweets, users | Yes | Type of compliance job to list. |

