# POST /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/UserDefinedMessageSubscriptions.json

**Resource:** [Api20100401UserDefinedMessageSubscription](../resources/Api20100401UserDefinedMessageSubscription.md)
**Subscribe to User Defined Messages for a given Call SID.**
**Operation ID:** `CreateUserDefinedMessageSubscription`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that subscribed to the User Defined Messages. |
| `CallSid` | path | string | Yes | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the User Defined Messages subscription is associated with. This refers to the Call SID that is producing the user defined messages. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.call.user_defined_message_subscription](../schemas/api-v2010-account-call-user/api-v2010-account-call-user-defined-message-subscription.md)

## Security

- **accountSid_authToken**
