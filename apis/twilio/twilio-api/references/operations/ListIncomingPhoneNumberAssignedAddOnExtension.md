# GET /2010-04-01/Accounts/{AccountSid}/IncomingPhoneNumbers/{ResourceSid}/AssignedAddOns/{AssignedAddOnSid}/Extensions.json

**Resource:** [Api20100401AssignedAddOnExtension](../resources/Api20100401AssignedAddOnExtension.md)
**Retrieve a list of Extensions for the Assigned Add-on.**
**Operation ID:** `ListIncomingPhoneNumberAssignedAddOnExtension`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the resources to read. |
| `ResourceSid` | path | string | Yes | The SID of the Phone Number to which the Add-on is assigned. |
| `AssignedAddOnSid` | path | string | Yes | The SID that uniquely identifies the assigned Add-on installation. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
