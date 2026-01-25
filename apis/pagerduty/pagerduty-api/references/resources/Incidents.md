# Incidents

An incident represents a problem or an issue that needs to be addressed and resolved. Incidents trigger on a service, which prompts notifications to go out to on-call responders per the service's escalation policy.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/incidents` | List incidents | [View](../operations/listIncidents.md) |
| PUT | `/incidents` | Manage incidents | [View](../operations/updateIncidents.md) |
| POST | `/incidents` | Create an Incident | [View](../operations/createIncident.md) |
| GET | `/incidents/{id}` | Get an incident | [View](../operations/getIncident.md) |
| PUT | `/incidents/{id}` | Update an incident | [View](../operations/updateIncident.md) |
| GET | `/incidents/{id}/alerts` | List alerts for an incident | [View](../operations/listIncidentAlerts.md) |
| PUT | `/incidents/{id}/alerts` | Manage alerts | [View](../operations/updateIncidentAlerts.md) |
| GET | `/incidents/{id}/alerts/{alert_id}` | Get an alert | [View](../operations/getIncidentAlert.md) |
| PUT | `/incidents/{id}/alerts/{alert_id}` | Update an alert | [View](../operations/updateIncidentAlert.md) |
| PUT | `/incidents/{id}/business_services/{business_service_id}/impacts` | Manually change an Incident's Impact on a Business Service. | [View](../operations/putIncidentManualBusinessServiceAssociation.md) |
| GET | `/incidents/{id}/business_services/impacts` | List Business Services impacted by the given Incident | [View](../operations/getIncidentImpactedBusinessServices.md) |
| GET | `/incidents/{id}/custom_fields/values` | Get Custom Field Values | [View](../operations/getIncidentFieldValues.md) |
| PUT | `/incidents/{id}/custom_fields/values` | Update Custom Field Values | [View](../operations/setIncidentFieldValues.md) |
| GET | `/incidents/{id}/log_entries` | List log entries for an incident | [View](../operations/listIncidentLogEntries.md) |
| PUT | `/incidents/{id}/merge` | Merge incidents | [View](../operations/mergeIncidents.md) |
| GET | `/incidents/{id}/notes` | List notes for an incident | [View](../operations/listIncidentNotes.md) |
| POST | `/incidents/{id}/notes` | Create a note on an incident | [View](../operations/createIncidentNote.md) |
| PUT | `/incidents/{id}/notes/{note_id}` | Update a note on an incident | [View](../operations/updateIncidentNote.md) |
| DELETE | `/incidents/{id}/notes/{note_id}` | Delete a note on an incident | [View](../operations/deleteIncidentNote.md) |
| GET | `/incidents/{id}/outlier_incident` | Get Outlier Incident | [View](../operations/getOutlierIncident.md) |
| GET | `/incidents/{id}/past_incidents` | Get Past Incidents | [View](../operations/getPastIncidents.md) |
| GET | `/incidents/{id}/related_incidents` | Get Related Incidents | [View](../operations/getRelatedIncidents.md) |
| POST | `/incidents/{id}/responder_requests` | Create a responder request for an incident | [View](../operations/createIncidentResponderRequest.md) |
| POST | `/incidents/{id}/snooze` | Snooze an incident | [View](../operations/createIncidentSnooze.md) |
| POST | `/incidents/{id}/status_updates` | Create a status update on an incident | [View](../operations/createIncidentStatusUpdate.md) |
| GET | `/incidents/{id}/status_updates/subscribers` | List Notification Subscribers | [View](../operations/getIncidentNotificationSubscribers.md) |
| POST | `/incidents/{id}/status_updates/subscribers` | Add Notification Subscribers | [View](../operations/createIncidentNotificationSubscribers.md) |
| POST | `/incidents/{id}/status_updates/unsubscribe` | Remove Notification Subscriber | [View](../operations/removeIncidentNotificationSubscribers.md) |
