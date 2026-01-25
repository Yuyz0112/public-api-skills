# api.v2010.account.sip.sip_domain

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the SipDomain resource. |
| `api_version` | string | No | The API version used to process the call. |
| `auth_type` | string | No | The types of authentication you have mapped to your domain. Can be: `IP_ACL` and `CREDENTIAL_LIST`. If you have both defined for your domain, both will be returned in a comma delimited string. If `auth_type` is not defined, the domain will not be able to receive any traffic. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was last updated specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `domain_name` | string | No | The unique address you reserve on Twilio to which you route your SIP traffic. Domain names can contain letters, digits, and "-" and must end with `sip.twilio.com`. |
| `friendly_name` | string | No | The string that you assigned to describe the resource. |
| `sid` | string | No | The unique string that that we created to identify the SipDomain resource. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |
| `voice_fallback_method` | enum: GET, POST | No | The HTTP method we use to call `voice_fallback_url`. Can be: `GET` or `POST`. |
| `voice_fallback_url` | string (uri) | No | The URL that we call when an error occurs while retrieving or executing the TwiML requested from `voice_url`. |
| `voice_method` | enum: GET, POST | No | The HTTP method we use to call `voice_url`. Can be: `GET` or `POST`. |
| `voice_status_callback_method` | enum: GET, POST | No | The HTTP method we use to call `voice_status_callback_url`. Either `GET` or `POST`. |
| `voice_status_callback_url` | string (uri) | No | The URL that we call to pass status parameters (such as call ended) to your application. |
| `voice_url` | string (uri) | No | The URL we call using the `voice_method` when the domain receives a call. |
| `subresource_uris` | object (uri-map) | No | A list of mapping resources associated with the SIP Domain resource identified by their relative URIs. |
| `sip_registration` | boolean | No | Whether to allow SIP Endpoints to register with the domain to receive calls. |
| `emergency_calling_enabled` | boolean | No | Whether emergency calling is enabled for the domain. If enabled, allows emergency calls on the domain from phone numbers with validated addresses. |
| `secure` | boolean | No | Whether secure SIP is enabled for the domain. If enabled, TLS will be enforced and SRTP will be negotiated on all incoming calls to this sip domain. |
| `byoc_trunk_sid` | string | No | The SID of the BYOC Trunk(Bring Your Own Carrier) resource that the Sip Domain will be associated with. |
| `emergency_caller_sid` | string | No | Whether an emergency caller sid is configured for the domain. If present, this phone number will be used as the callback for the emergency call. |

