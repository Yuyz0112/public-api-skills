# GET /incidents/{id}/outlier_incident

**Resource:** [Incidents](../resources/Incidents.md)
**Get Outlier Incident**
**Operation ID:** `getOutlierIncident`

Gets Outlier Incident information for a given Incident on its Service.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#outlier-incident)

Scoped OAuth requires: `incidents.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | Outlier Incident information calculated over the same Service as the given Incident. |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

