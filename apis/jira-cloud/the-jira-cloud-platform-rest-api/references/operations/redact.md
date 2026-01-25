# POST /rest/api/3/redact

**Resource:** [Issue redaction](../resources/Issue-redaction.md)
**Redact**
**Operation ID:** `redact`

Submit a job to redact issue field data. This will trigger the redaction of the data in the specified fields asynchronously.

The redaction status can be polled using the job id.

## Request Body

List of redaction requests

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [BulkRedactionRequest](../schemas/Bulk/BulkRedactionRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Returned if the job submission is successful. The response contains the job id. |
| 400 | Returned if the redaction request is invalid. |
| 401 | Returned if the user / app is not authorised to redact data |
| 403 | Returned if the AGP subscription is not present. |

## Security

- **basicAuth**
