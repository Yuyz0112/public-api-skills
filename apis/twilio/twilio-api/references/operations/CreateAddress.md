# POST /2010-04-01/Accounts/{AccountSid}/Addresses.json

**Resource:** [Api20100401Address](../resources/Api20100401Address.md)
**Operation ID:** `CreateAddress`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that will be responsible for the new Address resource. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.address](../schemas/api-v2010-account-address/api-v2010-account-address.md)

## Security

- **accountSid_authToken**
