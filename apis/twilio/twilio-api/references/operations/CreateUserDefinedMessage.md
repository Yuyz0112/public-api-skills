# POST /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/UserDefinedMessages.json

**Resource:** [Api20100401UserDefinedMessage](../resources/Api20100401UserDefinedMessage.md)
**Create a new User Defined Message for the given Call SID.**
**Operation ID:** `CreateUserDefinedMessage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created User Defined Message. |
| `CallSid` | path | string | Yes | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the User Defined Message is associated with. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.call.user_defined_message](../schemas/api-v2010-account-call-user/api-v2010-account-call-user-defined-message.md)

## Security

- **accountSid_authToken**
