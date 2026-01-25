# access_responses

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cf_resource_id` | string | No | The unique Cloudflare-generated Id of the SCIM resource. |
| `error_description` | string | No | The error message which is generated when the status of the SCIM request is 'FAILURE'. |
| `idp_id` | string | No | The unique Id of the IdP that has SCIM enabled. |
| `idp_resource_id` | string | No | The IdP-generated Id of the SCIM resource. |
| `logged_at` | [access_timestamp](access-timestamp.md) | No |  |
| `request_body` | string | No | The JSON-encoded string body of the SCIM request. |
| `request_method` | string | No | The request method of the SCIM request. |
| `resource_group_name` | string | No | The display name of the SCIM Group resource if it exists. |
| `resource_type` | string | No | The resource type of the SCIM request. |
| `resource_user_email` | string (email) | No | The email address of the SCIM User resource if it exists. |
| `status` | string | No | The status of the SCIM request. |

