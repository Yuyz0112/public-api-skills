# GET /2010-04-01/Accounts/{AccountSid}/SIP/Domains/{DomainSid}/IpAccessControlListMappings/{Sid}.json

**Resource:** [Api20100401IpAccessControlListMapping](../resources/Api20100401IpAccessControlListMapping.md)
**Fetch an IpAccessControlListMapping resource.**
**Operation ID:** `FetchSipIpAccessControlListMapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the Account that is responsible for this resource. |
| `DomainSid` | path | string | Yes | A 34 character string that uniquely identifies the SIP domain. |
| `Sid` | path | string | Yes | A 34 character string that uniquely identifies the resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.sip.sip_domain.sip_ip_access_control_list_mapping](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-domain-sip-ip-access-control-list-mapping.md)

## Security

- **accountSid_authToken**
