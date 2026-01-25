# GET /2/compliance/jobs

**Resource:** [Compliance](../resources/Compliance.md)
**Get Compliance Jobs**
**Operation ID:** `getComplianceJobs`

Retrieves a list of Compliance Jobs filtered by job type and optional status.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `type` | query | enum: tweets, users | Yes | Type of Compliance Job to list. |
| `status` | query | enum: created, in_progress, failed... | No | Status of Compliance Job to list. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2ComplianceJobsResponse](../schemas/Get/Get2ComplianceJobsResponse.md)

## Security

- **BearerToken**
