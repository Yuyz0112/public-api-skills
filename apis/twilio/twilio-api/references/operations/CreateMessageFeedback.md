# POST /2010-04-01/Accounts/{AccountSid}/Messages/{MessageSid}/Feedback.json

**Resource:** [Api20100401Feedback](../resources/Api20100401Feedback.md)
**Create Message Feedback to confirm a tracked user action was performed by the recipient of the associated Message**
**Operation ID:** `CreateMessageFeedback`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) associated with the Message resource for which to create MessageFeedback. |
| `MessageSid` | path | string | Yes | The SID of the Message resource for which to create MessageFeedback. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.message.message_feedback](../schemas/api-v2010-account-message-message/api-v2010-account-message-message-feedback.md)

## Security

- **accountSid_authToken**
