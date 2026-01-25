# GET /2010-04-01/Accounts/{AccountSid}/SIP/Domains/{DomainSid}/Auth/Calls/IpAccessControlListMappings/{Sid}.json

**Resource:** [Api20100401AuthCallsIpAccessControlListMapping](../resources/Api20100401AuthCallsIpAccessControlListMapping.md)
**Fetch a specific instance of an IP Access Control List mapping**
**Operation ID:** `FetchSipAuthCallsIpAccessControlListMapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the IpAccessControlListMapping resource to fetch. |
| `DomainSid` | path | string | Yes | The SID of the SIP domain that contains the resource to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the IpAccessControlListMapping resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.sip.sip_domain.sip_auth.sip_auth_calls.sip_auth_calls_ip_access_control_list_mapping](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-domain-sip-auth-sip-auth-calls-sip-auth-calls-ip-access-control-list-mapping.md)

## Security

- **accountSid_authToken**
