# POST /2010-04-01/Accounts/{AccountSid}/Applications.json

**Resource:** [Api20100401Application](../resources/Api20100401Application.md)
**Create a new application within your account**
**Operation ID:** `CreateApplication`

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

[api.v2010.account.application](../schemas/api-v2010-account-application/api-v2010-account-application.md)

## Security

- **accountSid_authToken**
