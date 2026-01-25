# api.v2010.account.incoming_phone_number.incoming_phone_number_assigned_add_on.incoming_phone_number_assigned_add_on_extension

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sid` | string | No | The unique string that that we created to identify the resource. |
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the resource. |
| `resource_sid` | string | No | The SID of the Phone Number to which the Add-on is assigned. |
| `assigned_add_on_sid` | string | No | The SID that uniquely identifies the assigned Add-on installation. |
| `friendly_name` | string | No | The string that you assigned to describe the resource. |
| `product_name` | string | No | A string that you assigned to describe the Product this Extension is used within. |
| `unique_name` | string | No | An application-defined string that uniquely identifies the resource. It can be used in place of the resource's `sid` in the URL to address the resource. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |
| `enabled` | boolean | No | Whether the Extension will be invoked. |

