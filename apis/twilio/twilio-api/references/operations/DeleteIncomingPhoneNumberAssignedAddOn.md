# DELETE /2010-04-01/Accounts/{AccountSid}/IncomingPhoneNumbers/{ResourceSid}/AssignedAddOns/{Sid}.json

**Resource:** [Api20100401AssignedAddOn](../resources/Api20100401AssignedAddOn.md)
**Remove the assignment of an Add-on installation from the Number specified.**
**Operation ID:** `DeleteIncomingPhoneNumberAssignedAddOn`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the resources to delete. |
| `ResourceSid` | path | string | Yes | The SID of the Phone Number to which the Add-on is assigned. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
