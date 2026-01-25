# POST /2010-04-01/Accounts/{AccountSid}/Tokens.json

**Resource:** [Api20100401Token](../resources/Api20100401Token.md)
**Create a new token for ICE servers**
**Operation ID:** `CreateToken`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that will create the resource. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.token](../schemas/api-v2010-account-token/api-v2010-account-token.md)

## Security

- **accountSid_authToken**
