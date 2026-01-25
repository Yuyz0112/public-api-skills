# cache-rules_origin_post_quantum_encryption

Instructs Cloudflare to use Post-Quantum (PQ) key agreement algorithms when connecting to your origin. Preferred instructs Cloudflare to opportunistically send a Post-Quantum keyshare in the first message to the origin (for fastest connections when the origin supports and prefers PQ), supported means that PQ algorithms are advertised but only used when requested by the origin, and off means that PQ algorithms are not advertised.

**Type:** allOf

## Composition

- [cache-rules_base](cache-rules-base.md)
- (inline schema)
