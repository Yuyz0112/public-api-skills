# api.v2010.account.usage.usage_record.usage_record_monthly

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that accrued the usage. |
| `api_version` | string | No | The API version used to create the resource. |
| `as_of` | string | No | Usage records up to date as of this timestamp, formatted as YYYY-MM-DDTHH:MM:SS+00:00. All timestamps are in GMT |
| `category` | string | No | The category of usage. For more information, see [Usage Categories](https://www.twilio.com/docs/usage/api/usage-record#usage-categories). |
| `count` | string | No | The number of usage events, such as the number of calls. |
| `count_unit` | string | No | The units in which `count` is measured, such as `calls` for calls or `messages` for SMS. |
| `description` | string | No | A plain-language description of the usage category. |
| `end_date` | string (date) | No | The last date for which usage is included in the UsageRecord. The date is specified in GMT and formatted as `YYYY-MM-DD`. |
| `price` | number | No | The total price of the usage in the currency specified in `price_unit` and associated with the account. |
| `price_unit` | string (currency) | No | The currency in which `price` is measured, in [ISO 4127](https://www.iso.org/iso/home/standards/currency_codes.htm) format, such as `usd`, `eur`, and `jpy`. |
| `start_date` | string (date) | No | The first date for which usage is included in this UsageRecord. The date is specified in GMT and formatted as `YYYY-MM-DD`. |
| `subresource_uris` | object (uri-map) | No | A list of related resources identified by their URIs. For more information, see [List Subresources](https://www.twilio.com/docs/usage/api/usage-record#list-subresources). |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |
| `usage` | string | No | The amount used to bill usage and measured in units described in `usage_unit`. |
| `usage_unit` | string | No | The units in which `usage` is measured, such as `minutes` for calls or `messages` for SMS. |

