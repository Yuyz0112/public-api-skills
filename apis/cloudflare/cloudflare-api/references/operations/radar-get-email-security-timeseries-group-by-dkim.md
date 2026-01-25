# GET /radar/email/security/timeseries_groups/dkim

**Resource:** [Radar Email Security](../resources/Radar-Email-Security.md)
**Get email DKIM validation time series**
**Operation ID:** `radar-get-email-security-timeseries-group-by-dkim`
⚠️ **Deprecated**

Retrieves the distribution of emails by DKIM (DomainKeys Identified Mail) validation over time.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `aggInterval` | query | enum: 15m, 1h, 1d... | No | Aggregation interval of the results (e.g., in 15 minutes or 1 hour intervals). Refer to [Aggregation intervals](https://developers.cloudflare.com/radar/concepts/aggregation-intervals/). |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `arc` | query | string[] | No | Filters results by ARC (Authenticated Received Chain) validation. |
| `dmarc` | query | string[] | No | Filters results by DMARC (Domain-based Message Authentication, Reporting and Conformance) validation status. |
| `spf` | query | string[] | No | Filters results by SPF (Sender Policy Framework) validation status. |
| `tlsVersion` | query | string[] | No | Filters results by TLS version. |
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
