# DELETE /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/UserDefinedMessageSubscriptions/{Sid}.json

**Resource:** [Api20100401UserDefinedMessageSubscription](../resources/Api20100401UserDefinedMessageSubscription.md)
**Delete a specific User Defined Message Subscription.**
**Operation ID:** `DeleteUserDefinedMessageSubscription`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that subscribed to the User Defined Messages. |
| `CallSid` | path | string | Yes | The SID of the [Call](https://www.twilio.com/docs/voice/api/call-resource) the User Defined Message Subscription is associated with. This refers to the Call SID that is producing the User Defined Messages. |
| `Sid` | path | string | Yes | The SID that uniquely identifies this User Defined Message Subscription. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
