# PUT /incidents

**Resource:** [Incidents](../resources/Incidents.md)
**Manage incidents**
**Operation ID:** `updateIncidents`

Acknowledge, resolve, escalate or reassign one or more incidents.

An incident represents a problem or an issue that needs to be addressed and resolved.

A maximum of 250 incidents may be updated at a time. If more than this number of incidents are given, the API will respond with status 413 (Request Entity Too Large).

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#incidents)

Scoped OAuth requires: `incidents.write`

This API operation has operation specific rate limits. See the [Rate Limits](https://developer.pagerduty.com/docs/72d3b724589e3-rest-api-rate-limits) page for more information.


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | All of the updates succeeded. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 413 | (reference) |
| 429 | (reference) |

