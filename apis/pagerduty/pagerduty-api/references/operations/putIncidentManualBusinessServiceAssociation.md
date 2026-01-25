# PUT /incidents/{id}/business_services/{business_service_id}/impacts

**Resource:** [Incidents](../resources/Incidents.md)
**Manually change an Incident's Impact on a Business Service.**
**Operation ID:** `putIncidentManualBusinessServiceAssociation`

Change Impact of an Incident on a Business Service.
Scoped OAuth requires: `incidents.write`


## Request Body

The `impacted` relation will cause the Business Service and any Services that it supports to become impacted by this incident.

The `not_impacted` relation will remove the Incident's Impact from the specified Business Service.

The effect of adding or removing Impact to a Business Service in this way will also change the propagation of Impact to other Services supported by that Business Service.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |
| 429 | (reference) |

