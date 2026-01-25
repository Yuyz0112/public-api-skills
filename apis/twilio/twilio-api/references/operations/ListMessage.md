# GET /2010-04-01/Accounts/{AccountSid}/Messages.json

**Resource:** [Api20100401Message](../resources/Api20100401Message.md)
**Retrieve a list of Message resources associated with a Twilio Account**
**Operation ID:** `ListMessage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) associated with the Message resources. |
| `To` | query | string (phone-number) | No | Filter by recipient. For example: Set this parameter to `+15558881111` to retrieve a list of Message resources sent to `+15558881111`. |
| `From` | query | string (phone-number) | No | Filter by sender. For example: Set this parameter to `+15552229999` to retrieve a list of Message resources sent by `+15552229999`. |
| `DateSent` | query | string (date-time) | No | Filter by Message `sent_date`. Accepts GMT dates in the following formats: `YYYY-MM-DD` (to find Messages with a specific `sent_date`), `<=YYYY-MM-DD` (to find Messages with `sent_date`s on and before a specific date), and `>=YYYY-MM-DD` (to find Messages with `sent_dates` on and after a specific date). |
| `DateSent<` | query | string (date-time) | No | Filter by Message `sent_date`. Accepts GMT dates in the following formats: `YYYY-MM-DD` (to find Messages with a specific `sent_date`), `<=YYYY-MM-DD` (to find Messages with `sent_date`s on and before a specific date), and `>=YYYY-MM-DD` (to find Messages with `sent_dates` on and after a specific date). |
| `DateSent>` | query | string (date-time) | No | Filter by Message `sent_date`. Accepts GMT dates in the following formats: `YYYY-MM-DD` (to find Messages with a specific `sent_date`), `<=YYYY-MM-DD` (to find Messages with `sent_date`s on and before a specific date), and `>=YYYY-MM-DD` (to find Messages with `sent_dates` on and after a specific date). |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
