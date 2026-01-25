# GET /2010-04-01/Accounts/{AccountSid}/Recordings/{Sid}.json

**Resource:** [Api20100401Recording](../resources/Api20100401Recording.md)
**Fetch an instance of a recording**
**Operation ID:** `FetchRecording`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Recording resource to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Recording resource to fetch. |
| `IncludeSoftDeleted` | query | boolean | No | A boolean parameter indicating whether to retrieve soft deleted recordings or not. Recordings metadata are kept after deletion for a retention period of 40 days. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.recording](../schemas/api-v2010-account-recording/api-v2010-account-recording.md)

## Security

- **accountSid_authToken**
