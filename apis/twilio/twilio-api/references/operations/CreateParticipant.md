# POST /2010-04-01/Accounts/{AccountSid}/Conferences/{ConferenceSid}/Participants.json

**Resource:** [Api20100401Participant](../resources/Api20100401Participant.md)
**Operation ID:** `CreateParticipant`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that will create the resource. |
| `ConferenceSid` | path | string | Yes | The SID of the participant's conference. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.conference.participant](../schemas/api-v2010-account-conference-participant/api-v2010-account-conference-participant.md)

## Security

- **accountSid_authToken**
