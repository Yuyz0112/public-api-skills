# GET /business_services/impactors

**Resource:** [Business Services](../resources/Business-Services.md)
**List Impactors affecting Business Services**
**Operation ID:** `getBusinessServiceTopLevelImpactors`

Retrieve a list of Impactors for the top-level Business Services on the account. Impactors are currently limited to Incidents.

This endpoint does not return an exhaustive list of Impactors but rather provides access to the highest priority Impactors for the Business Services in question up to the limit of 200.

To get Impactors for a specific set of Business Services, use the `ids[]` parameter.

The returned Impactors are sorted first by priority and secondarily by their creation date.
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

