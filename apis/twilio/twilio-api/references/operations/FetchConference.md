# GET /2010-04-01/Accounts/{AccountSid}/Conferences/{Sid}.json

**Resource:** [Api20100401Conference](../resources/Api20100401Conference.md)
**Fetch an instance of a conference**
**Operation ID:** `FetchConference`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Conference resource(s) to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Conference resource to fetch |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.conference](../schemas/api-v2010-account-conference/api-v2010-account-conference.md)

## Security

- **accountSid_authToken**
