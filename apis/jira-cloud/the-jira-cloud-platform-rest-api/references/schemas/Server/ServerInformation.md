# ServerInformation

Details about the Jira instance.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `baseUrl` | string | No | The base URL of the Jira instance. |
| `buildDate` | string (date-time) | No | The timestamp when the Jira version was built. |
| `buildNumber` | integer (int32) | No | The build number of the Jira version. |
| `deploymentType` | string | No | The type of server deployment. This is always returned as *Cloud*. |
| `displayUrl` | string | No | The display URL of the Jira instance. |
| `displayUrlConfluence` | string | No | The display URL of Confluence. |
| `displayUrlServicedeskHelpCenter` | string | No | The display URL of the Servicedesk Help Center. |
| `healthChecks` | HealthCheckResult[] | No | Jira instance health check results. Deprecated and no longer returned. |
| `scmInfo` | string | No | The unique identifier of the Jira version. |
| `serverTime` | string (date-time) | No | The time in Jira when this request was responded to. |
| `serverTimeZone` | string | No | The default timezone of the Jira server. In a format known as Olson Time Zones, IANA Time Zones or TZ Database Time Zones. |
| `serverTitle` | string | No | The name of the Jira instance. |
| `version` | string | No | The version of Jira. |
| `versionNumbers` | integer[] | No | The major, minor, and revision version numbers of the Jira version. |

