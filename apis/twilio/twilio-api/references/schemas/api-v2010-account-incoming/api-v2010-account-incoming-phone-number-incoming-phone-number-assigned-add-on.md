# api.v2010.account.incoming_phone_number.incoming_phone_number_assigned_add_on

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sid` | string | No | The unique string that that we created to identify the resource. |
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the resource. |
| `resource_sid` | string | No | The SID of the Phone Number to which the Add-on is assigned. |
| `friendly_name` | string | No | The string that you assigned to describe the resource. |
| `description` | string | No | A short description of the functionality that the Add-on provides. |
| `configuration` | any | No | A JSON string that represents the current configuration of this Add-on installation. |
| `unique_name` | string | No | An application-defined string that uniquely identifies the resource. It can be used in place of the resource's `sid` in the URL to address the resource. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was last updated specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |
| `subresource_uris` | object (uri-map) | No | A list of related resources identified by their relative URIs. |

