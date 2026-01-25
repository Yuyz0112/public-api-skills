# Analytics

Provides enriched incident data.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/analytics/metrics/incidents/all` | Get aggregated incident data | [View](../operations/getAnalyticsMetricsIncidentsAll.md) |
| POST | `/analytics/metrics/incidents/escalation_policies` | Get aggregated escalation policy data | [View](../operations/getAnalyticsMetricsIncidentsEscalationPolicy.md) |
| POST | `/analytics/metrics/incidents/escalation_policies/all` | Get aggregated metrics for all escalation policies | [View](../operations/getAnalyticsMetricsIncidentsEscalationPolicyAll.md) |
| POST | `/analytics/metrics/incidents/services` | Get aggregated service data | [View](../operations/getAnalyticsMetricsIncidentsService.md) |
| POST | `/analytics/metrics/incidents/services/all` | Get aggregated metrics for all services | [View](../operations/getAnalyticsMetricsIncidentsServiceAll.md) |
| POST | `/analytics/metrics/incidents/teams` | Get aggregated team data | [View](../operations/getAnalyticsMetricsIncidentsTeam.md) |
| POST | `/analytics/metrics/incidents/teams/all` | Get aggregated metrics for all teams | [View](../operations/getAnalyticsMetricsIncidentsTeamAll.md) |
| POST | `/analytics/metrics/pd_advance_usage/features` | Get aggregated PD Advance usage data | [View](../operations/getAnalyticsMetricsPdAdvanceUsageFeatures.md) |
| POST | `/analytics/metrics/responders/all` | Get aggregated metrics for all responders | [View](../operations/getAnalyticsMetricsRespondersAll.md) |
| POST | `/analytics/metrics/responders/teams` | Get responder data aggregated by team | [View](../operations/getAnalyticsMetricsRespondersTeam.md) |
| POST | `/analytics/metrics/users/all` | Get aggregated metrics for all users | [View](../operations/getAnalyticsMetricsUsersAll.md) |
| POST | `/analytics/raw/incidents` | Get raw data - multiple incidents | [View](../operations/getAnalyticsIncidents.md) |
| GET | `/analytics/raw/incidents/{id}` | Get raw data - single incident | [View](../operations/getAnalyticsIncidentsById.md) |
| GET | `/analytics/raw/incidents/{id}/responses` | Get raw responses from a single incident | [View](../operations/getAnalyticsIncidentResponsesById.md) |
| POST | `/analytics/raw/responders/{responder_id}/incidents` | Get raw incidents for a single responder_id | [View](../operations/getAnalyticsResponderIncidents.md) |
| POST | `/analytics/raw/users` | Get raw user analytics data | [View](../operations/getAnalyticsUsers.md) |
