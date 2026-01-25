# DELETE /2010-04-01/Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}/IpAddresses/{Sid}.json

**Resource:** [Api20100401SipIpAddress](../resources/Api20100401SipIpAddress.md)
**Delete an IpAddress resource.**
**Operation ID:** `DeleteSipIpAddress`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the [Account](https://www.twilio.com/docs/iam/api/account) responsible for this resource. |
| `IpAccessControlListSid` | path | string | Yes | The IpAccessControlList Sid that identifies the IpAddress resources to delete. |
| `Sid` | path | string | Yes | A 34 character string that uniquely identifies the resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
