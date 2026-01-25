# mcn_create_onramp_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `adopted_hub_id` | [mcn_resource_id](mcn-resource-id.md) | No |  |
| `attached_hubs` | mcn_resource_id[] | No |  |
| `attached_vpcs` | mcn_resource_id[] | No |  |
| `cloud_asn` | integer (uint32) | No | the ASN to use on the cloud side. If unset or zero, the cloud's default will be used. |
| `cloud_type` | [mcn_onramp_cloud_type](mcn-onramp-cloud-type.md) | Yes |  |
| `description` | string | No |  |
| `dynamic_routing` | boolean | Yes | if set to true, install_routes_in_cloud and install_routes_in_magic_wan should be set to false |
| `hub_provider_id` | [mcn_provider_id](mcn-provider-id.md) | No |  |
| `install_routes_in_cloud` | boolean | Yes |  |
| `install_routes_in_magic_wan` | boolean | Yes |  |
| `manage_hub_to_hub_attachments` | boolean | No |  |
| `manage_vpc_to_hub_attachments` | boolean | No |  |
| `name` | string | Yes |  |
| `region` | string | No |  |
| `type` | [mcn_onramp_type](mcn-onramp-type.md) | Yes |  |
| `vpc` | [mcn_resource_id](mcn-resource-id.md) | No |  |

