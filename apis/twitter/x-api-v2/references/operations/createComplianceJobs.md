# POST /2/compliance/jobs

**Resource:** [Compliance](../resources/Compliance.md)
**Create Compliance Job**
**Operation ID:** `createComplianceJobs`

Creates a new Compliance Job for the specified job type.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateComplianceJobRequest](../schemas/Create/CreateComplianceJobRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[CreateComplianceJobResponse](../schemas/Create/CreateComplianceJobResponse.md)

## Security

- **BearerToken**
