# access_scim_config

Configuration for provisioning to this application via SCIM. This is currently in closed beta.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `authentication` | any | No |  |
| `deactivate_on_delete` | boolean | No | If false, propagates DELETE requests to the target application for SCIM resources. If true, sets 'active' to false on the SCIM resource. Note: Some targets do not support DELETE operations. |
| `enabled` | boolean | No | Whether SCIM provisioning is turned on for this application. |
| `idp_uid` | string | Yes | The UID of the IdP to use as the source for SCIM resources to provision to this application. |
| `mappings` | access_scim_config_mapping[] | No | A list of mappings to apply to SCIM resources before provisioning them in this application. These can transform or filter the resources to be provisioned. |
| `remote_uri` | string | Yes | The base URI for the application's SCIM-compatible API. |

