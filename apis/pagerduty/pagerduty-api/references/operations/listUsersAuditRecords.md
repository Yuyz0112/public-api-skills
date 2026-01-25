# GET /users/{id}/audit/records

**Resource:** [Users](../resources/Users.md)
**List audit records for a user**
**Operation ID:** `listUsersAuditRecords`

The response will include audit records with changes that are made to the identified user not changes made by the identified user.


The returned records are sorted by the `execution_time` from newest to oldest.

See [`Cursor-based pagination`](https://developer.pagerduty.com/docs/rest-api-v2/pagination/) for instructions on how to paginate through the result set.

For more information see the [Audit API Document](https://developer.pagerduty.com/docs/rest-api-v2/audit-records-api/).

Scoped OAuth requires: `audit_records.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | Records matching the query criteria. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[AuditRecordResponseSchema](../schemas/Audit/AuditRecordResponseSchema.md)

