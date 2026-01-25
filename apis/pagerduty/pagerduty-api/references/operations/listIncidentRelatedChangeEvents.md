# GET /incidents/{id}/related_change_events

**Resource:** [Change Events](../resources/Change-Events.md)
**List related Change Events for an Incident**
**Operation ID:** `listIncidentRelatedChangeEvents`

List related Change Events for an Incident, as well as the reason these changes are correlated with the incident.

Change events represent service changes such as deploys, build completion, and configuration changes, providing information that is critical during incident triage or hypercare. For more information on change events, see [Change Events](https://support.pagerduty.com/docs/change-events).

The Change Correlation feature provides incident responders with recent change events that are most relevant to that incident. Change Correlation informs the responder why a particular change event was surfaced and correlated to an incident based on three key factors which include time, related service, or intelligence (machine learning).

Scoped OAuth requires: `incidents.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The array of Change Events returned by the query. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

