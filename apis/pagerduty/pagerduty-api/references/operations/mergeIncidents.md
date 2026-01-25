# PUT /incidents/{id}/merge

**Resource:** [Incidents](../resources/Incidents.md)
**Merge incidents**
**Operation ID:** `mergeIncidents`

Merge a list of source incidents into the target [incident](https://developer.pagerduty.com/api-reference/a47605517c19a-api-concepts#incidents).

After the merge is performed the target incident will contain the source incidents' [alerts](https://developer.pagerduty.com/api-reference/a47605517c19a-api-concepts#alerts),
and the source incidents will be resolved.

Only incidents that have alerts or incidents that were created manually in the UI can be merged.

Open incidents cannot be merged into a resolved incident.

An incident cannot have more than 1000 alerts. The server will return an error if merging the source incidents
will result in the target incident having more than 1000 alerts.

Scoped OAuth requires: `incidents.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The target incident, which now contains all the alerts from the source incident. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

