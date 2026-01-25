# GET /2010-04-01/Accounts/{AccountSid}/Recordings/{ReferenceSid}/AddOnResults/{AddOnResultSid}/Payloads.json

**Resource:** [Api20100401Payload](../resources/Api20100401Payload.md)
**Retrieve a list of payloads belonging to the AddOnResult**
**Operation ID:** `ListRecordingAddOnResultPayload`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Recording AddOnResult Payload resources to read. |
| `ReferenceSid` | path | string | Yes | The SID of the recording to which the AddOnResult resource that contains the payloads to read belongs. |
| `AddOnResultSid` | path | string | Yes | The SID of the AddOnResult to which the payloads to read belongs. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
