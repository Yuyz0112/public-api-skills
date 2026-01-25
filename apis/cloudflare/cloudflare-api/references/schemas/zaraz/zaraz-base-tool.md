# zaraz_base-tool

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `blockingTriggers` | string[] | Yes | List of blocking trigger IDs |
| `defaultFields` | object | Yes | Default fields for tool's actions |
| `defaultPurpose` | string | No | Default consent purpose ID |
| `enabled` | boolean | Yes | Whether tool is enabled |
| `name` | string | Yes | Tool's name defined by the user |
| `vendorName` | string | No | Vendor name for TCF compliant consent modal, required for Custom Managed Components and Custom HTML tool with a defaultPurpose assigned |
| `vendorPolicyUrl` | string | No | Vendor's Privacy Policy URL for TCF compliant consent modal, required for Custom Managed Components and Custom HTML tool with a defaultPurpose assigned |

