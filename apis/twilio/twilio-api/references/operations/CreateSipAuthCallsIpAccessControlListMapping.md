# POST /2010-04-01/Accounts/{AccountSid}/SIP/Domains/{DomainSid}/Auth/Calls/IpAccessControlListMappings.json

**Resource:** [Api20100401AuthCallsIpAccessControlListMapping](../resources/Api20100401AuthCallsIpAccessControlListMapping.md)
**Create a new IP Access Control List mapping**
**Operation ID:** `CreateSipAuthCallsIpAccessControlListMapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that will create the resource. |
| `DomainSid` | path | string | Yes | The SID of the SIP domain that will contain the new resource. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.sip.sip_domain.sip_auth.sip_auth_calls.sip_auth_calls_ip_access_control_list_mapping](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-domain-sip-auth-sip-auth-calls-sip-auth-calls-ip-access-control-list-mapping.md)

## Security

- **accountSid_authToken**
