# DELETE /2010-04-01/Accounts/{AccountSid}/SIP/Domains/{DomainSid}/IpAccessControlListMappings/{Sid}.json

**Resource:** [Api20100401IpAccessControlListMapping](../resources/Api20100401IpAccessControlListMapping.md)
**Delete an IpAccessControlListMapping resource.**
**Operation ID:** `DeleteSipIpAccessControlListMapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the Account that is responsible for this resource. |
| `DomainSid` | path | string | Yes | A 34 character string that uniquely identifies the SIP domain. |
| `Sid` | path | string | Yes | A 34 character string that uniquely identifies the resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
