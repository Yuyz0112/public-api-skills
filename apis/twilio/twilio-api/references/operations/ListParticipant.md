# GET /2010-04-01/Accounts/{AccountSid}/Conferences/{ConferenceSid}/Participants.json

**Resource:** [Api20100401Participant](../resources/Api20100401Participant.md)
**Retrieve a list of participants belonging to the account used to make the request**
**Operation ID:** `ListParticipant`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Participant resources to read. |
| `ConferenceSid` | path | string | Yes | The SID of the conference with the participants to read. |
| `Muted` | query | boolean | No | Whether to return only participants that are muted. Can be: `true` or `false`. |
| `Hold` | query | boolean | No | Whether to return only participants that are on hold. Can be: `true` or `false`. |
| `Coaching` | query | boolean | No | Whether to return only participants who are coaching another call. Can be: `true` or `false`. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
