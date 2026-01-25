# POST /2010-04-01/Accounts/{AccountSid}/Messages/{Sid}.json

**Resource:** [Api20100401Message](../resources/Api20100401Message.md)
**Update a Message resource (used to redact Message `body` text and to cancel not-yet-sent messages)**
**Operation ID:** `UpdateMessage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Message resources to update. |
| `Sid` | path | string | Yes | The SID of the Message resource to be updated |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.message](../schemas/api-v2010-account-message/api-v2010-account-message.md)

## Security

- **accountSid_authToken**
