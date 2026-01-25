# GET /2010-04-01/Accounts/{AccountSid}/Messages/{MessageSid}/Media/{Sid}.json

**Resource:** [Api20100401MediaInstance](../resources/Api20100401MediaInstance.md)
**Fetch a single Media resource associated with a specific Message resource**
**Operation ID:** `FetchMedia`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) associated with the Media resource. |
| `MessageSid` | path | string | Yes | The SID of the Message resource that is associated with the Media resource. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Media resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.message.media](../schemas/api-v2010-account-message-media/api-v2010-account-message-media.md)

## Security

- **accountSid_authToken**
