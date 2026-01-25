# copilot-organization-details

Information about the seat breakdown and policies set for an organization with a Copilot Business or Copilot Enterprise subscription.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `seat_breakdown` | [copilot-organization-seat-breakdown](copilot-organization-seat-breakdown.md) | Yes |  |
| `public_code_suggestions` | enum: allow, block, unconfigured | Yes | The organization policy for allowing or blocking suggestions matching public code (duplication detection filter). |
| `ide_chat` | enum: enabled, disabled, unconfigured | No | The organization policy for allowing or disallowing Copilot Chat in the IDE. |
| `platform_chat` | enum: enabled, disabled, unconfigured | No | The organization policy for allowing or disallowing Copilot features on GitHub.com. |
| `cli` | enum: enabled, disabled, unconfigured | No | The organization policy for allowing or disallowing Copilot in the CLI. |
| `seat_management_setting` | enum: assign_all, assign_selected, disabled... | Yes | The mode of assigning new seats. |
| `plan_type` | enum: business, enterprise | No | The Copilot plan of the organization, or the parent enterprise, when applicable. |

