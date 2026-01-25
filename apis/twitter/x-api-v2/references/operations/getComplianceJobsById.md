# GET /2/compliance/jobs/{id}

**Resource:** [Compliance](../resources/Compliance.md)
**Get Compliance Job by ID**
**Operation ID:** `getComplianceJobsById`

Retrieves details of a specific Compliance Job by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | JobId | Yes | The ID of the Compliance Job to retrieve. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2ComplianceJobsIdResponse](../schemas/Get/Get2ComplianceJobsIdResponse.md)

## Security

- **BearerToken**
