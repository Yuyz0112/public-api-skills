# GET /rest/api/3/redact/status/{jobId}

**Resource:** [Issue redaction](../resources/Issue-redaction.md)
**Get redaction status**
**Operation ID:** `getRedactionStatus`

Retrieves the current status of a redaction job ID.

The jobStatus will be one of the following:

 *  IN\_PROGRESS - The redaction job is currently in progress
 *  COMPLETED - The redaction job has completed successfully.
 *  PENDING - The redaction job has not started yet

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `jobId` | path | string | Yes | Redaction job id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the job status is successfully retrieved. |
| 403 | Returned if the AGP subscription is not present. |
| 404 | Returned if the job id is not found. |

**Success Response Schema:**

[RedactionJobStatusResponse](../schemas/Redaction/RedactionJobStatusResponse.md)

## Security

- **basicAuth**
