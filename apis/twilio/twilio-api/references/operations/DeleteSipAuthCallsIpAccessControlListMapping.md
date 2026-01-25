# DELETE /2010-04-01/Accounts/{AccountSid}/SIP/Domains/{DomainSid}/Auth/Calls/IpAccessControlListMappings/{Sid}.json

**Resource:** [Api20100401AuthCallsIpAccessControlListMapping](../resources/Api20100401AuthCallsIpAccessControlListMapping.md)
**Delete an IP Access Control List mapping from the requested domain**
**Operation ID:** `DeleteSipAuthCallsIpAccessControlListMapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the IpAccessControlListMapping resources to delete. |
| `DomainSid` | path | string | Yes | The SID of the SIP domain that contains the resources to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the IpAccessControlListMapping resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
