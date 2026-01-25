# POST /2010-04-01/Accounts/{AccountSid}/Conferences/{Sid}.json

**Resource:** [Api20100401Conference](../resources/Api20100401Conference.md)
**Operation ID:** `UpdateConference`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Conference resource(s) to update. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Conference resource to update |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.conference](../schemas/api-v2010-account-conference/api-v2010-account-conference.md)

## Security

- **accountSid_authToken**
