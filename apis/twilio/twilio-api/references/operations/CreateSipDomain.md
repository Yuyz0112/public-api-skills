# POST /2010-04-01/Accounts/{AccountSid}/SIP/Domains.json

**Resource:** [Api20100401Domain](../resources/Api20100401Domain.md)
**Create a new Domain**
**Operation ID:** `CreateSipDomain`

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

[api.v2010.account.sip.sip_domain](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-domain.md)

## Security

- **accountSid_authToken**
