# GET /vendors/{id}

**Resource:** [Vendors](../resources/Vendors.md)
**Get a vendor**
**Operation ID:** `getVendor`

Get details about one specific vendor.

A PagerDuty Vendor represents a specific type of integration. AWS Cloudwatch, Splunk, Datadog are all examples of vendors

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#vendors)

Scoped OAuth requires: `vendors.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The vendor requested |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

