# GET /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Notifications.json

**Resource:** [Api20100401CallNotification](../resources/Api20100401CallNotification.md)
**Operation ID:** `ListCallNotification`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Call Notification resources to read. |
| `CallSid` | path | string | Yes | The [Call](https://www.twilio.com/docs/voice/api/call-resource) SID of the Call Notification resources to read. |
| `Log` | query | integer | No | Only read notifications of the specified log level. Can be:  `0` to read only ERROR notifications or `1` to read only WARNING notifications. By default, all notifications are read. |
| `MessageDate` | query | string (date) | No | Only show notifications for the specified date, formatted as `YYYY-MM-DD`. You can also specify an inequality, such as `<=YYYY-MM-DD` for messages logged at or before midnight on a date, or `>=YYYY-MM-DD` for messages logged at or after midnight on a date. |
| `MessageDate<` | query | string (date) | No | Only show notifications for the specified date, formatted as `YYYY-MM-DD`. You can also specify an inequality, such as `<=YYYY-MM-DD` for messages logged at or before midnight on a date, or `>=YYYY-MM-DD` for messages logged at or after midnight on a date. |
| `MessageDate>` | query | string (date) | No | Only show notifications for the specified date, formatted as `YYYY-MM-DD`. You can also specify an inequality, such as `<=YYYY-MM-DD` for messages logged at or before midnight on a date, or `>=YYYY-MM-DD` for messages logged at or after midnight on a date. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
