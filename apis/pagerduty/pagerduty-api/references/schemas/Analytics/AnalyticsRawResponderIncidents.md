# AnalyticsRawResponderIncidents

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `incident_created_at` | string | No | Timestamp of when the incident was created. |
| `incident_description` | string | No | The incident description. |
| `incident_id` | string | No | Incident ID |
| `incident_number` | integer | No | The PagerDuty incident number. |
| `incident_priority_id` | string | No | ID of the incident's priority level. |
| `incident_priority_name` | string | No | The user-provided short name of the priority. |
| `incident_priority_order` | integer | No | The numerical value used to sort priorities. Higher values are higher priority. |
| `incident_urgency` | string | No | Notification level |
| `mean_time_to_acknowledge_seconds` | integer | No | Mean time from this user being assigned to an incident until this user acknowledges the incident. |
| `responder_id` | string | No | ID of the responder. |
| `responder_name` | string | No | Name of the responder. |
| `service_id` | string | No | ID of the service that the incident triggered on. |
| `service_name` | string | No | Name of the service that the incident triggered on. |
| `service_team_id` | string | No | ID of the team that owns the related service. |
| `service_team_name` | string | No | Name of the team that owns the related service. |
| `total_acknowledgements` | integer | No | Total acknowledgements from the responder on the incident. |
| `total_business_hour_interruptions` | integer | No | Total number of unique interruptions during business hours; 8am-6pm Mon-Fri, based on the user’s time zone. |
| `total_engaged_seconds` | integer | No | Total engaged time across all responders for incidents. Engaged time is measured from
the time a user engages with an incident (by acknowledging or accepting a responder request)
until the incident is resolved. This may include periods in which the incidents were snoozed. |
| `total_interruptions` | integer | No | Total number of unique interruptions for the responder during the incident. |
| `total_manual_escalations_from` | integer | No | Total times the responder was manually escalated away from the incident. |
| `total_manual_escalations_to` | integer | No | Total times the responder was manually escalated to the incident. |
| `total_off_hour_interruptions` | string | No | Total number of unique interruptions during off hours; 6pm-10pm Mon-Fri and all day Sat-Sun, based on the user’s time zone. |
| `total_reassignments_from` | integer | No | Total times the responder was reassigned away from the incident. |
| `total_reassignments_to` | integer | No | Total times the responder was reassigned to the incident. |
| `total_sleep_hour_interruptions` | integer | No | Total number of unique interruptions during sleep hours; 10pm-8am every day, based on the user’s time zone. |
| `total_timeout_escalations_from` | integer | No | Total times the responder was escalated away from the incident due to timeout. |
| `total_timeout_escalations_to` | integer | No | Total times the responder was escalated to the incident due to timeout. |

