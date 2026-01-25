# DELETE /2010-04-01/Accounts/{AccountSid}/Conferences/{ConferenceSid}/Participants/{CallSid}.json

**Resource:** [Api20100401Participant](../resources/Api20100401Participant.md)
**Kick a participant from a given conference**
**Operation ID:** `DeleteParticipant`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Participant resources to delete. |
| `ConferenceSid` | path | string | Yes | The SID of the conference with the participants to delete. |
| `CallSid` | path | string | Yes | The [Call](https://www.twilio.com/docs/voice/api/call-resource) SID or label of the participant to delete. Non URL safe characters in a label must be percent encoded, for example, a space character is represented as %20. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
