# GET /radar/leaked_credential_checks/summary/compromised

**Resource:** [Radar Leaked Credential Checks](../resources/Radar-Leaked-Credential-Checks.md)
**Get HTTP authentication requests by compromised credential status summary**
**Operation ID:** `radar-get-leaked-credential-checks-summary-by-compromised`
⚠️ **Deprecated**

Retrieves the distribution of HTTP authentication requests by compromised credential status.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `botClass` | query | string[] | No | Filters results by bot class. Refer to [Bot classes](https://developers.cloudflare.com/radar/concepts/bot-classes/). |
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
