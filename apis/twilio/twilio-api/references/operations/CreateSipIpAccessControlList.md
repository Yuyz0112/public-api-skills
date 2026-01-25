# POST /2010-04-01/Accounts/{AccountSid}/SIP/IpAccessControlLists.json

**Resource:** [Api20100401IpAccessControlList](../resources/Api20100401IpAccessControlList.md)
**Create a new IpAccessControlList resource**
**Operation ID:** `CreateSipIpAccessControlList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the [Account](https://www.twilio.com/docs/iam/api/account) responsible for this resource. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.sip.sip_ip_access_control_list](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-ip-access-control-list.md)

## Security

- **accountSid_authToken**
