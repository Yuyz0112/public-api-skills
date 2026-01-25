# GET /business_services/impacts

**Resource:** [Business Services](../resources/Business-Services.md)
**List Business Services sorted by impacted status**
**Operation ID:** `getBusinessServiceImpacts`

Retrieve a list top-level Business Services sorted by highest Impact with `status` included.
When called without the `ids[]` parameter, this endpoint does not return an exhaustive list of Business Services but rather provides access to the most impacted up to the limit of 200.

The returned Business Services are sorted first by Impact, secondarily by most recently impacted, and finally by name.

To get impact information about a specific set of Business Services, use the `ids[]` parameter.
Scoped OAuth requires: `services.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |
| 429 | (reference) |

