# Schedules

A Schedule determines the time periods that users are On-Call.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/schedules` | List schedules | [View](../operations/listSchedules.md) |
| POST | `/schedules` | Create a schedule | [View](../operations/createSchedule.md) |
| GET | `/schedules/{id}` | Get a schedule | [View](../operations/getSchedule.md) |
| PUT | `/schedules/{id}` | Update a schedule | [View](../operations/updateSchedule.md) |
| DELETE | `/schedules/{id}` | Delete a schedule | [View](../operations/deleteSchedule.md) |
| GET | `/schedules/{id}/audit/records` | List audit records for a schedule | [View](../operations/listSchedulesAuditRecords.md) |
| GET | `/schedules/{id}/overrides` | List overrides | [View](../operations/listScheduleOverrides.md) |
| POST | `/schedules/{id}/overrides` | Create one or more overrides | [View](../operations/createScheduleOverride.md) |
| DELETE | `/schedules/{id}/overrides/{override_id}` | Delete an override | [View](../operations/deleteScheduleOverride.md) |
| GET | `/schedules/{id}/users` | List users on call. | [View](../operations/listScheduleUsers.md) |
| POST | `/schedules/preview` | Preview a schedule | [View](../operations/createSchedulePreview.md) |
