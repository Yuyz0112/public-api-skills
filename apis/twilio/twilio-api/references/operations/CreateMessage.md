# POST /2010-04-01/Accounts/{AccountSid}/Messages.json

**Resource:** [Api20100401Message](../resources/Api20100401Message.md)
**Send a message**
**Operation ID:** `CreateMessage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) creating the Message resource. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.message](../schemas/api-v2010-account-message/api-v2010-account-message.md)

## Security

- **accountSid_authToken**
