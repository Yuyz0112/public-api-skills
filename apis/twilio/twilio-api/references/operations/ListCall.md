# GET /2010-04-01/Accounts/{AccountSid}/Calls.json

**Resource:** [Api20100401Call](../resources/Api20100401Call.md)
**Retrieves a collection of calls made to and from your account**
**Operation ID:** `ListCall`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Call resource(s) to read. |
| `To` | query | string (phone-number) | No | Only show calls made to this phone number, SIP address, Client identifier or SIM SID. |
| `From` | query | string (phone-number) | No | Only include calls from this phone number, SIP address, Client identifier or SIM SID. |
| `ParentCallSid` | query | string | No | Only include calls spawned by calls with this SID. |
| `Status` | query | call_enum_status | No | The status of the calls to include. Can be: `queued`, `ringing`, `in-progress`, `canceled`, `completed`, `failed`, `busy`, or `no-answer`. |
| `StartTime` | query | string (date-time) | No | Only include calls that started on this date. Specify a date as `YYYY-MM-DD` in UTC, for example: `2009-07-06`, to read only calls that started on this date. You can also specify an inequality, such as `StartTime<=YYYY-MM-DD`, to read calls that started on or before midnight of this date, and `StartTime>=YYYY-MM-DD` to read calls that started on or after midnight of this date. |
| `StartTime<` | query | string (date-time) | No | Only include calls that started on this date. Specify a date as `YYYY-MM-DD` in UTC, for example: `2009-07-06`, to read only calls that started on this date. You can also specify an inequality, such as `StartTime<=YYYY-MM-DD`, to read calls that started on or before midnight of this date, and `StartTime>=YYYY-MM-DD` to read calls that started on or after midnight of this date. |
| `StartTime>` | query | string (date-time) | No | Only include calls that started on this date. Specify a date as `YYYY-MM-DD` in UTC, for example: `2009-07-06`, to read only calls that started on this date. You can also specify an inequality, such as `StartTime<=YYYY-MM-DD`, to read calls that started on or before midnight of this date, and `StartTime>=YYYY-MM-DD` to read calls that started on or after midnight of this date. |
| `EndTime` | query | string (date-time) | No | Only include calls that ended on this date. Specify a date as `YYYY-MM-DD` in UTC, for example: `2009-07-06`, to read only calls that ended on this date. You can also specify an inequality, such as `EndTime<=YYYY-MM-DD`, to read calls that ended on or before midnight of this date, and `EndTime>=YYYY-MM-DD` to read calls that ended on or after midnight of this date. |
| `EndTime<` | query | string (date-time) | No | Only include calls that ended on this date. Specify a date as `YYYY-MM-DD` in UTC, for example: `2009-07-06`, to read only calls that ended on this date. You can also specify an inequality, such as `EndTime<=YYYY-MM-DD`, to read calls that ended on or before midnight of this date, and `EndTime>=YYYY-MM-DD` to read calls that ended on or after midnight of this date. |
| `EndTime>` | query | string (date-time) | No | Only include calls that ended on this date. Specify a date as `YYYY-MM-DD` in UTC, for example: `2009-07-06`, to read only calls that ended on this date. You can also specify an inequality, such as `EndTime<=YYYY-MM-DD`, to read calls that ended on or before midnight of this date, and `EndTime>=YYYY-MM-DD` to read calls that ended on or after midnight of this date. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
