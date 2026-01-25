# GET /2010-04-01/Accounts/{AccountSid}/IncomingPhoneNumbers/{ResourceSid}/AssignedAddOns/{AssignedAddOnSid}/Extensions/{Sid}.json

**Resource:** [Api20100401AssignedAddOnExtension](../resources/Api20100401AssignedAddOnExtension.md)
**Fetch an instance of an Extension for the Assigned Add-on.**
**Operation ID:** `FetchIncomingPhoneNumberAssignedAddOnExtension`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the resource to fetch. |
| `ResourceSid` | path | string | Yes | The SID of the Phone Number to which the Add-on is assigned. |
| `AssignedAddOnSid` | path | string | Yes | The SID that uniquely identifies the assigned Add-on installation. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.incoming_phone_number.incoming_phone_number_assigned_add_on.incoming_phone_number_assigned_add_on_extension](../schemas/api-v2010-account-incoming/api-v2010-account-incoming-phone-number-incoming-phone-number-assigned-add-on-incoming-phone-number-assigned-add-on-extension.md)

## Security

- **accountSid_authToken**
