# GET /2010-04-01/Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}/IpAddresses/{Sid}.json

**Resource:** [Api20100401SipIpAddress](../resources/Api20100401SipIpAddress.md)
**Read one IpAddress resource.**
**Operation ID:** `FetchSipIpAddress`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the [Account](https://www.twilio.com/docs/iam/api/account) responsible for this resource. |
| `IpAccessControlListSid` | path | string | Yes | The IpAccessControlList Sid that identifies the IpAddress resources to fetch. |
| `Sid` | path | string | Yes | A 34 character string that uniquely identifies the IpAddress resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.sip.sip_ip_access_control_list.sip_ip_address](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-ip-access-control-list-sip-ip-address.md)

## Security

- **accountSid_authToken**
