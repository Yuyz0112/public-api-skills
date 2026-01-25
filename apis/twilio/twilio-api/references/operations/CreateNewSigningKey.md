# POST /2010-04-01/Accounts/{AccountSid}/SigningKeys.json

**Resource:** [Api20100401NewSigningKey](../resources/Api20100401NewSigningKey.md)
**Create a new Signing Key for the account making the request.**
**Operation ID:** `CreateNewSigningKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that will be responsible for the new Key resource. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.new_signing_key](../schemas/api-v2010-account-new/api-v2010-account-new-signing-key.md)

## Security

- **accountSid_authToken**
