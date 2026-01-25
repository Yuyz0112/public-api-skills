# GET /analytics/raw/incidents/{id}/responses

**Resource:** [Analytics](../resources/Analytics.md)
**Get raw responses from a single incident**
**Operation ID:** `getAnalyticsIncidentResponsesById`

Provides enriched responder data for a single incident.

Example metrics include Time to Respond, Responder Type, and Response Status. See metric definitions below.

<!-- theme: info -->
> **Note:** Analytics data is updated once per day. It takes up to 24 hours before new incident responses appear in the Analytics API.
Scoped OAuth requires: `analytics.read`


## Request Body

Parameters to apply to the dataset.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |
| 404 | (reference) |
| 429 | (reference) |

