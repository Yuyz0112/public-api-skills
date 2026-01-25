# GET /radar/ct/summary/{dimension}

**Resource:** [Radar Certificate Transparency](../resources/Radar-Certificate-Transparency.md)
**Get certificate distribution by dimension**
**Operation ID:** `radar-get-ct-summary`

Retrieves an aggregated summary of certificates grouped by the specified dimension.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dimension` | path | enum: CA, CA_OWNER, DURATION... | Yes | Specifies the certificate attribute by which to group the results. |
| `name` | query | string[] | No | Array of names used to label the series in the response. |
| `dateRange` | query | string[] | No | Filters results by date range. For example, use `7d` and `7dcontrol` to compare this week with the previous week. Use this parameter or set specific start and end dates (`dateStart` and `dateEnd` parameters). |
| `dateStart` | query | string[] | No | Start of the date range. |
| `dateEnd` | query | string[] | No | End of the date range (inclusive). |
| `limitPerGroup` | query | integer | No | Limits the number of objects per group to the top items within the specified time range. When item count exceeds the limit, extra items appear grouped under an "other" category. |
| `ca` | query | string[] | No | Filters results by certificate authority. |
| `caOwner` | query | string[] | No | Filters results by certificate authority owner. |
| `duration` | query | string[] | No | Filters results by certificate duration. |
| `entryType` | query | string[] | No | Filters results by entry type (certificate vs. pre-certificate). |
| `expirationStatus` | query | string[] | No | Filters results by expiration status (expired vs. valid). |
| `hasIps` | query | boolean[] | No | Filters results based on whether the certificates are bound to specific IP addresses. |
| `hasWildcards` | query | boolean[] | No | Filters results based on whether the certificates contain wildcard domains. |
| `log` | query | string[] | No | Filters results by certificate log. |
| `logApi` | query | string[] | No | Filters results by certificate log API (RFC6962 vs. static). |
| `logOperator` | query | string[] | No | Filters results by certificate log operator. |
| `publicKeyAlgorithm` | query | string[] | No | Filters results by public key algorithm. |
| `signatureAlgorithm` | query | string[] | No | Filters results by signature algorithm. |
| `tld` | query | string[] | No | Filters results by top-level domain. |
| `validationLevel` | query | string[] | No | Filters results by validation level. |
| `uniqueEntries` | query | string[] | No | Specifies whether to filter out duplicate certificates and pre-certificates. Set to true for unique entries only. |
| `normalization` | query | enum: RAW_VALUES, PERCENTAGE | No | Normalization method applied to the results. Refer to [Normalization methods](https://developers.cloudflare.com/radar/concepts/normalization/). |
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
