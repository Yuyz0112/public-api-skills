# POST /2010-04-01/Accounts/{Sid}.json

**Resource:** [Api20100401Account](../resources/Api20100401Account.md)
**Modify the properties of a given Account**
**Operation ID:** `UpdateAccount`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `Sid` | path | string | Yes | The Account Sid that uniquely identifies the account to update |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account](../schemas/api-v2010-account/api-v2010-account.md)

## Security

- **accountSid_authToken**
