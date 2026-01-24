# POST /v1/credit_notes

**Resource:** [credit_notes](../resources/credit-notes.md)
**Create a credit note**
**Operation ID:** `PostCreditNotes`

<p>Issue a credit note to adjust the amount of a finalized invoice. A credit note will first reduce the invoice’s <code>amount_remaining</code> (and <code>amount_due</code>), but not below zero.
This amount is indicated by the credit note’s <code>pre_payment_amount</code>. The excess amount is indicated by <code>post_payment_amount</code>, and it can result in any combination of the following:</p>

<ul>
<li>Refunds: create a new refund (using <code>refund_amount</code>) or link existing refunds (using <code>refunds</code>).</li>
<li>Customer balance credit: credit the customer’s balance (using <code>credit_amount</code>) which will be automatically applied to their next invoice when it’s finalized.</li>
<li>Outside of Stripe credit: record the amount that is or will be credited outside of Stripe (using <code>out_of_band_amount</code>).</li>
</ul>

<p>The sum of refunds, customer balance credits, and outside of Stripe credits must equal the <code>post_payment_amount</code>.</p>

<p>You may issue multiple credit notes for an invoice. Each credit note may increment the invoice’s <code>pre_payment_credit_notes_amount</code>,
<code>post_payment_credit_notes_amount</code>, or both, depending on the invoice’s <code>amount_remaining</code> at the time of credit note creation.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[credit_note](../schemas/credit/credit-note.md)

