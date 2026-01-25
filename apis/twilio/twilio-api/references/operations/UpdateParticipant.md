# POST /2010-04-01/Accounts/{AccountSid}/Conferences/{ConferenceSid}/Participants/{CallSid}.json

**Resource:** [Api20100401Participant](../resources/Api20100401Participant.md)
**Update the properties of the participant**
**Operation ID:** `UpdateParticipant`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Participant resources to update. |
| `ConferenceSid` | path | string | Yes | The SID of the conference with the participant to update. |
| `CallSid` | path | string | Yes | The [Call](https://www.twilio.com/docs/voice/api/call-resource) SID or label of the participant to update. Non URL safe characters in a label must be percent encoded, for example, a space character is represented as %20. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.conference.participant](../schemas/api-v2010-account-conference-participant/api-v2010-account-conference-participant.md)

## Security

- **accountSid_authToken**
