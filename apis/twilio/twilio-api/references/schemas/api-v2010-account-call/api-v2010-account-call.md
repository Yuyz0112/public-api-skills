# api.v2010.account.call

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sid` | string | No | The unique string that we created to identify this Call resource. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in UTC that this resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in UTC that this resource was last updated, specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `parent_call_sid` | string | No | The SID that identifies the call that created this leg. |
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created this Call resource. |
| `to` | string | No | The phone number, SIP address, Client identifier or SIM SID that received this call. Phone numbers are in [E.164](https://www.twilio.com/docs/glossary/what-e164) format (e.g., +16175551212). SIP addresses are formatted as `name@company.com`. Client identifiers are formatted `client:name`. SIM SIDs are formatted as `sim:sid`. |
| `to_formatted` | string | No | The phone number, SIP address or Client identifier that received this call. Formatted for display. Non-North American phone numbers are in [E.164](https://www.twilio.com/docs/glossary/what-e164) format (e.g., +442071838750). |
| `from` | string | No | The phone number, SIP address, Client identifier or SIM SID that made this call. Phone numbers are in [E.164](https://www.twilio.com/docs/glossary/what-e164) format (e.g., +16175551212). SIP addresses are formatted as `name@company.com`. Client identifiers are formatted `client:name`. SIM SIDs are formatted as `sim:sid`. |
| `from_formatted` | string | No | The calling phone number, SIP address, or Client identifier formatted for display. Non-North American phone numbers are in [E.164](https://www.twilio.com/docs/glossary/what-e164) format (e.g., +442071838750). |
| `phone_number_sid` | string | No | If the call was inbound, this is the SID of the IncomingPhoneNumber resource that received the call. If the call was outbound, it is the SID of the OutgoingCallerId resource from which the call was placed. |
| `status` | [call_enum_status](call-enum-status.md) | No |  |
| `start_time` | string (date-time-rfc-2822) | No | The start time of the call, given as UTC in [RFC 2822](https://www.php.net/manual/en/class.datetime.php#datetime.constants.rfc2822) format. Empty if the call has not yet been dialed. |
| `end_time` | string (date-time-rfc-2822) | No | The time the call ended, given as UTC in [RFC 2822](https://www.php.net/manual/en/class.datetime.php#datetime.constants.rfc2822) format. Empty if the call did not complete successfully. |
| `duration` | string | No | The length of the call in seconds. This value is empty for busy, failed, unanswered, or ongoing calls. |
| `price` | string | No | The charge for this call, in the currency associated with the account. Populated after the call is completed. May not be immediately available. The price associated with a call only reflects the charge for connectivity.  Charges for other call-related features such as Answering Machine Detection, Text-To-Speech, and SIP REFER are not included in this value. |
| `price_unit` | string (currency) | No | The currency in which `Price` is measured, in [ISO 4127](https://www.iso.org/iso/home/standards/currency_codes.htm) format (e.g., `USD`, `EUR`, `JPY`). Always capitalized for calls. |
| `direction` | string | No | A string describing the direction of the call. Can be: `inbound` for inbound calls, `outbound-api` for calls initiated via the REST API or `outbound-dial` for calls initiated by a `<Dial>` verb. Using [Elastic SIP Trunking](https://www.twilio.com/docs/sip-trunking), the values can be [`trunking-terminating`](https://www.twilio.com/docs/sip-trunking#termination) for outgoing calls from your communications infrastructure to the PSTN or [`trunking-originating`](https://www.twilio.com/docs/sip-trunking#origination) for incoming calls to your communications infrastructure from the PSTN. |
| `answered_by` | string | No | Either `human` or `machine` if this call was initiated with answering machine detection. Empty otherwise. |
| `api_version` | string | No | The API version used to create the call. |
| `forwarded_from` | string | No | The forwarding phone number if this call was an incoming call forwarded from another number (depends on carrier supporting forwarding). Otherwise, empty. |
| `group_sid` | string | No | The Group SID associated with this call. If no Group is associated with the call, the field is empty. |
| `caller_name` | string | No | The caller's name if this call was an incoming call to a phone number with caller ID Lookup enabled. Otherwise, empty. |
| `queue_time` | string | No | The wait time in milliseconds before the call is placed. |
| `trunk_sid` | string | No | The unique identifier of the trunk resource that was used for this call. The field is empty if the call was not made using a SIP trunk or if the call is not terminated. |
| `uri` | string | No | The URI of this resource, relative to `https://api.twilio.com`. |
| `subresource_uris` | object (uri-map) | No | A list of subresources available to this call, identified by their URIs relative to `https://api.twilio.com`. |

