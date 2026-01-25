# dispute_enhanced_evidence_visa_compliance

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fee_acknowledged` | boolean | Yes | A field acknowledging the fee incurred when countering a Visa compliance dispute. If this field is set to true, evidence can be submitted for the compliance dispute. Stripe collects a 500 USD (or local equivalent) amount to cover the network costs associated with resolving compliance disputes. Stripe refunds the 500 USD network fee if you win the dispute. |

