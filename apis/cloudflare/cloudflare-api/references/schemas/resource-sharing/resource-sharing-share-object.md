# resource-sharing_share_object

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_id` | [resource-sharing_account_id](resource-sharing-account-id.md) | Yes |  |
| `account_name` | [resource-sharing_account_name](resource-sharing-account-name.md) | Yes |  |
| `associated_recipient_count` | integer | No | The number of recipients in the 'associated' state. This field is only included when requested via the 'include_recipient_counts' parameter. |
| `associating_recipient_count` | integer | No | The number of recipients in the 'associating' state. This field is only included when requested via the 'include_recipient_counts' parameter. |
| `created` | [resource-sharing_created](resource-sharing-created.md) | Yes |  |
| `disassociated_recipient_count` | integer | No | The number of recipients in the 'disassociated' state. This field is only included when requested via the 'include_recipient_counts' parameter. |
| `disassociating_recipient_count` | integer | No | The number of recipients in the 'disassociating' state. This field is only included when requested via the 'include_recipient_counts' parameter. |
| `id` | [resource-sharing_share_id](resource-sharing-share-id.md) | Yes |  |
| `kind` | [resource-sharing_share_kind](resource-sharing-share-kind.md) | No |  |
| `modified` | [resource-sharing_modified](resource-sharing-modified.md) | Yes |  |
| `name` | [resource-sharing_share_name](resource-sharing-share-name.md) | Yes |  |
| `organization_id` | [resource-sharing_organization_id](resource-sharing-organization-id.md) | Yes |  |
| `resources` | resource-sharing_share_resource_object[] | No | A list of resources that are part of the share. This field is only included when requested via the 'include_resources' parameter. |
| `status` | [resource-sharing_share_status](resource-sharing-share-status.md) | Yes |  |
| `target_type` | [resource-sharing_share_target_type](resource-sharing-share-target-type.md) | Yes |  |

