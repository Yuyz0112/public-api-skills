# POST /2010-04-01/Accounts/{AccountSid}/SIP/Domains/{Sid}.json

**Resource:** [Api20100401Domain](../resources/Api20100401Domain.md)
**Update the attributes of a domain**
**Operation ID:** `UpdateSipDomain`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the SipDomain resource to update. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the SipDomain resource to update. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.sip.sip_domain](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-domain.md)

## Security

- **accountSid_authToken**
