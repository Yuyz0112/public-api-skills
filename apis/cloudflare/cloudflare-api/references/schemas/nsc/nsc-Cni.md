# nsc_Cni

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | [nsc_AccountTag](nsc-AccountTag.md) | Yes |  |
| `bgp` | [nsc_BgpControl](nsc-BgpControl.md) | No |  |
| `cust_ip` | string (A.B.C.D/N) | Yes | Customer end of the point-to-point link

This should always be inside the same prefix as `p2p_ip`. |
| `id` | string (uuid) | Yes |  |
| `interconnect` | string | Yes | Interconnect identifier hosting this CNI |
| `magic` | [nsc_MagicSettings](nsc-MagicSettings.md) | Yes |  |
| `p2p_ip` | string (A.B.C.D/N) | Yes | Cloudflare end of the point-to-point link |

