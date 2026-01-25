# POST /2010-04-01/Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}/IpAddresses.json

**Resource:** [Api20100401SipIpAddress](../resources/Api20100401SipIpAddress.md)
**Create a new IpAddress resource.**
**Operation ID:** `CreateSipIpAddress`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the [Account](https://www.twilio.com/docs/iam/api/account) responsible for this resource. |
| `IpAccessControlListSid` | path | string | Yes | The IpAccessControlList Sid with which to associate the created IpAddress resource. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.sip.sip_ip_access_control_list.sip_ip_address](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-ip-access-control-list-sip-ip-address.md)

## Security

- **accountSid_authToken**
