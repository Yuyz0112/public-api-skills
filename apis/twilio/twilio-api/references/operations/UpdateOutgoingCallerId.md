# POST /2010-04-01/Accounts/{AccountSid}/OutgoingCallerIds/{Sid}.json

**Resource:** [Api20100401OutgoingCallerId](../resources/Api20100401OutgoingCallerId.md)
**Updates the caller-id**
**Operation ID:** `UpdateOutgoingCallerId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the OutgoingCallerId resources to update. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the OutgoingCallerId resource to update. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.outgoing_caller_id](../schemas/api-v2010-account-outgoing/api-v2010-account-outgoing-caller-id.md)

## Security

- **accountSid_authToken**
