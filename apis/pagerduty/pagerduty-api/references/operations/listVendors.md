# GET /vendors

**Resource:** [Vendors](../resources/Vendors.md)
**List vendors**
**Operation ID:** `listVendors`

List all vendors.

A PagerDuty Vendor represents a specific type of integration. AWS Cloudwatch, Splunk, Datadog are all examples of vendors

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#vendors)

Scoped OAuth requires: `vendors.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of vendors. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

