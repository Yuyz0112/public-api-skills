# GET /2010-04-01/Accounts/{AccountSid}/SIP/IpAccessControlLists/{Sid}.json

**Resource:** [Api20100401IpAccessControlList](../resources/Api20100401IpAccessControlList.md)
**Fetch a specific instance of an IpAccessControlList**
**Operation ID:** `FetchSipIpAccessControlList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the [Account](https://www.twilio.com/docs/iam/api/account) responsible for this resource. |
| `Sid` | path | string | Yes | A 34 character string that uniquely identifies the resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.sip.sip_ip_access_control_list](../schemas/api-v2010-account-sip-sip/api-v2010-account-sip-sip-ip-access-control-list.md)

## Security

- **accountSid_authToken**
