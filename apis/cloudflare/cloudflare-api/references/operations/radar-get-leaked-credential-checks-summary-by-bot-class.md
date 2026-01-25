# GET /radar/leaked_credential_checks/summary/bot_class

**Resource:** [Radar Leaked Credential Checks](../resources/Radar-Leaked-Credential-Checks.md)
**Get HTTP authentication requests by bot class summary**
**Operation ID:** `radar-get-leaked-credential-checks-summary-by-bot-class`
⚠️ **Deprecated**

Retrieves the distribution of HTTP authentication requests by bot class.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `compromised` | query | string[] | No | Filters results by compromised credential status (clean vs. compromised). |
| `format` | query | enum: JSON, CSV | No | Format in which results will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| 400 | Bad request. |

## Security

- **api_email**
- **api_key**
- **api_token**
