# Change Events

Change Events enable you to send informational events about recent changes such as code deploys and system config changes from any system that can make an outbound HTTP connection. These events do not create incidents and do not send notifications; they are shown in context with incidents on the same PagerDuty service.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/change_events` | List Change Events | [View](../operations/listChangeEvents.md) |
| POST | `/change_events` | Create a Change Event | [View](../operations/createChangeEvent.md) |
| GET | `/change_events/{id}` | Get a Change Event | [View](../operations/getChangeEvent.md) |
| PUT | `/change_events/{id}` | Update a Change Event | [View](../operations/updateChangeEvent.md) |
| GET | `/incidents/{id}/related_change_events` | List related Change Events for an Incident | [View](../operations/listIncidentRelatedChangeEvents.md) |
| GET | `/services/{id}/change_events` | List Change Events for a service | [View](../operations/listServiceChangeEvents.md) |
