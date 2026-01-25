# dispute_evidence_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `due_by` | integer (unix-time) | No | Date by which evidence must be submitted in order to successfully challenge dispute. Will be 0 if the customer's bank or credit card company doesn't allow a response for this particular dispute. |
| `enhanced_eligibility` | [dispute_enhanced_eligibility](dispute-enhanced-eligibility.md) | Yes |  |
| `has_evidence` | boolean | Yes | Whether evidence has been staged for this dispute. |
| `past_due` | boolean | Yes | Whether the last evidence submission was submitted past the due date. Defaults to `false` if no evidence submissions have occurred. If `true`, then delivery of the latest evidence is *not* guaranteed. |
| `submission_count` | integer | Yes | The number of times evidence has been submitted. Typically, you may only submit evidence once. |

