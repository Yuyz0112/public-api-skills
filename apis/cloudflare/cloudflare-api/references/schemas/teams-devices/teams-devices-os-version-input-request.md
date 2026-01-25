# teams-devices_os_version_input_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `operating_system` | enum: windows | Yes | Operating System. |
| `operator` | enum: <, <=, >... | Yes | Operator. |
| `os_distro_name` | string | No | Operating System Distribution Name (linux only). |
| `os_distro_revision` | string | No | Version of OS Distribution (linux only). |
| `os_version_extra` | string | No | Additional operating system version details. For Windows, the UBR (Update Build Revision). For Mac or iOS, the Product Version Extra. For Linux, the distribution name and version. |
| `version` | string | Yes | Version of OS. |

