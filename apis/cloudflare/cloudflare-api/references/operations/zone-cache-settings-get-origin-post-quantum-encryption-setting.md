# GET /zones/{zone_id}/cache/origin_post_quantum_encryption

**Resource:** [Origin Post-Quantum](../resources/Origin-Post-Quantum.md)
**Get Origin Post-Quantum Encryption setting**
**Operation ID:** `zone-cache-settings-get-origin-post-quantum-encryption-setting`

Instructs Cloudflare to use Post-Quantum (PQ) key agreement algorithms when connecting to your origin. Preferred instructs Cloudflare to opportunistically send a Post-Quantum keyshare in the first message to the origin (for fastest connections when the origin supports and prefers PQ), supported means that PQ algorithms are advertised but only used when requested by the origin, and off means that PQ algorithms are not advertised.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cache-rules_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Origin Post-Quantum Encryption setting response. |
| 4XX | Get Origin Post-Quantum Encryption setting response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
