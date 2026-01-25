# POST /2010-04-01/Accounts/{AccountSid}/SIP/Domains/{DomainSid}/IpAccessControlListMappings.json

**Resource:** [Api20100401IpAccessControlListMapping](../resources/Api20100401IpAccessControlListMapping.md)
**Create a new IpAccessControlListMapping resource.**
**Operation ID:** `CreateSipIpAccessControlListMapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the Account that is responsible for this resource. |
| `DomainSid` | path | string | Yes | A 34 character string that uniquely identifies the SIP domain. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.sip.sip_domain.sip_ip_access_control_list_mapping](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-domain-sip-ip-access-control-list-mapping.md)

## Security

- **accountSid_authToken**
