# GET /2010-04-01/Accounts/{AccountSid}/Usage/Triggers.json

**Resource:** [Api20100401Trigger](../resources/Api20100401Trigger.md)
**Retrieve a list of usage-triggers belonging to the account used to make the request**
**Operation ID:** `ListUsageTrigger`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the UsageTrigger resources to read. |
| `Recurring` | query | usage_trigger_enum_recurring | No | The frequency of recurring UsageTriggers to read. Can be: `daily`, `monthly`, or `yearly` to read recurring UsageTriggers. An empty value or a value of `alltime` reads non-recurring UsageTriggers. |
| `TriggerBy` | query | usage_trigger_enum_trigger_field | No | The trigger field of the UsageTriggers to read.  Can be: `count`, `usage`, or `price` as described in the [UsageRecords documentation](https://www.twilio.com/docs/usage/api/usage-record#usage-count-price). |
| `UsageCategory` | query | string | No | The usage category of the UsageTriggers to read. Must be a supported [usage categories](https://www.twilio.com/docs/usage/api/usage-record#usage-categories). |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
