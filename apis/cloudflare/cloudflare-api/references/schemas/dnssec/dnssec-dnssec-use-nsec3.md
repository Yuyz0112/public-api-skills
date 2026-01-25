# dnssec_dnssec_use_nsec3

If true, enables the use of NSEC3 together with DNSSEC on the zone.
Combined with setting dnssec_presigned to true, this enables the use of
NSEC3 records when transferring in from an external provider.
If dnssec_presigned is instead set to false (default), NSEC3 records will be
generated and signed at request time.

See [DNSSEC with NSEC3](https://developers.cloudflare.com/dns/dnssec/enable-nsec3/) for details.

**Type:** primitive

