# DELETE /2010-04-01/Accounts/{AccountSid}/SIP/IpAccessControlLists/{Sid}.json

**Resource:** [Api20100401IpAccessControlList](../resources/Api20100401IpAccessControlList.md)
**Delete an IpAccessControlList from the requested account**
**Operation ID:** `DeleteSipIpAccessControlList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The unique id of the [Account](https://www.twilio.com/docs/iam/api/account) responsible for this resource. |
| `Sid` | path | string | Yes | A 34 character string that uniquely identifies the resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
