# GET /2010-04-01/Accounts/{AccountSid}/Recordings.json

**Resource:** [Api20100401Recording](../resources/Api20100401Recording.md)
**Retrieve a list of recordings belonging to the account used to make the request**
**Operation ID:** `ListRecording`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Recording resources to read. |
| `DateCreated` | query | string (date-time) | No | Only include recordings that were created on this date. Specify a date as `YYYY-MM-DD` in GMT, for example: `2009-07-06`, to read recordings that were created on this date. You can also specify an inequality, such as `DateCreated<=YYYY-MM-DD`, to read recordings that were created on or before midnight of this date, and `DateCreated>=YYYY-MM-DD` to read recordings that were created on or after midnight of this date. |
| `DateCreated<` | query | string (date-time) | No | Only include recordings that were created on this date. Specify a date as `YYYY-MM-DD` in GMT, for example: `2009-07-06`, to read recordings that were created on this date. You can also specify an inequality, such as `DateCreated<=YYYY-MM-DD`, to read recordings that were created on or before midnight of this date, and `DateCreated>=YYYY-MM-DD` to read recordings that were created on or after midnight of this date. |
| `DateCreated>` | query | string (date-time) | No | Only include recordings that were created on this date. Specify a date as `YYYY-MM-DD` in GMT, for example: `2009-07-06`, to read recordings that were created on this date. You can also specify an inequality, such as `DateCreated<=YYYY-MM-DD`, to read recordings that were created on or before midnight of this date, and `DateCreated>=YYYY-MM-DD` to read recordings that were created on or after midnight of this date. |
| `CallSid` | query | string | No | The [Call](https://www.twilio.com/docs/voice/api/call-resource) SID of the resources to read. |
| `ConferenceSid` | query | string | No | The Conference SID that identifies the conference associated with the recording to read. |
| `IncludeSoftDeleted` | query | boolean | No | A boolean parameter indicating whether to retrieve soft deleted recordings or not. Recordings metadata are kept after deletion for a retention period of 40 days. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
