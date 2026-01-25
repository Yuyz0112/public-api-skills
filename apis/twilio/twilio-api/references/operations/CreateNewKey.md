# POST /2010-04-01/Accounts/{AccountSid}/Keys.json

**Resource:** [Api20100401NewKey](../resources/Api20100401NewKey.md)
**Operation ID:** `CreateNewKey`

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

[api.v2010.account.new_key](../schemas/api-v2010-account-new/api-v2010-account-new-key.md)

## Security

- **accountSid_authToken**
