# TimeTrackingConfiguration

Details of the time tracking configuration.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultUnit` | enum: minute, hour, day... | Yes | The default unit of time applied to logged time. |
| `timeFormat` | enum: pretty, days, hours | Yes | The format that will appear on an issue's *Time Spent* field. |
| `workingDaysPerWeek` | number (double) | Yes | The number of days in a working week. |
| `workingHoursPerDay` | number (double) | Yes | The number of hours in a working day. |

