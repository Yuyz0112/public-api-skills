# GET /audit/records

**Resource:** [Audit](../resources/Audit.md)
**List audit records**
**Operation ID:** `listAuditRecords`

List audit trail records matching provided query params or default criteria.

The returned records are sorted by the `execution_time` from newest to oldest.

See [`Cursor-based pagination`](https://developer.pagerduty.com/docs/rest-api-v2/pagination/) for instructions on how to paginate through the result set.

Only admins, account owners, or global API tokens on PagerDuty account [pricing plans](https://www.pagerduty.com/pricing) with the "Audit Trail" feature can access this endpoint.

For other role based access to audit records by resource ID, see the resource's API documentation.

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

