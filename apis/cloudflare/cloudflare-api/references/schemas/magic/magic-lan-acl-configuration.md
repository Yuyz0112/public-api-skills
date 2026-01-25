# magic_lan-acl-configuration

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `lan_id` | string | Yes | The identifier for the LAN you want to create an ACL policy with. |
| `lan_name` | string | No | The name of the LAN based on the provided lan_id. |
| `port_ranges` | magic_acl-port-range[] | No | Array of port ranges on the provided LAN that will be included in the ACL. If no ports or port rangess are provided, communication on any port on this LAN is allowed. |
| `ports` | magic_port[] | No | Array of ports on the provided LAN that will be included in the ACL. If no ports or port ranges are provided, communication on any port on this LAN is allowed. |
| `subnets` | magic_acl-subnet[] | No | Array of subnet IPs within the LAN that will be included in the ACL. If no subnets are provided, communication on any subnets on this LAN are allowed. |

