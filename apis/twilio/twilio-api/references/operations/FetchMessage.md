# GET /2010-04-01/Accounts/{AccountSid}/Messages/{Sid}.json

**Resource:** [Api20100401Message](../resources/Api20100401Message.md)
**Fetch a specific Message**
**Operation ID:** `FetchMessage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) associated with the Message resource |
| `Sid` | path | string | Yes | The SID of the Message resource to be fetched |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.message](../schemas/api-v2010-account-message/api-v2010-account-message.md)

## Security

- **accountSid_authToken**
