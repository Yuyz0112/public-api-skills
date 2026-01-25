# POST /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Streams.json

**Resource:** [Api20100401Stream](../resources/Api20100401Stream.md)
**Create a Stream**
**Operation ID:** `CreateStream`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created this Stream resource. |
| `CallSid` | path | string | Yes | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the Stream resource is associated with. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.call.stream](../schemas/api-v2010-account-call-stream/api-v2010-account-call-stream.md)

## Security

- **accountSid_authToken**
