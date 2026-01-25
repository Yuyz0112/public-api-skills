# POST /v1/invoices/{invoice}/lines/{line_item_id}

**Resource:** [invoices](../resources/invoices.md)
**Update an invoice's line item**
**Operation ID:** `PostInvoicesInvoiceLinesLineItemId`

<p>Updates an invoice’s line item. Some fields, such as <code>tax_amounts</code>, only live on the invoice line item,
so they can only be updated through this endpoint. Other fields, such as <code>amount</code>, live on both the invoice
item and the invoice line item, so updates on this endpoint will propagate to the invoice item as well.
Updating an invoice’s line item is only possible before the invoice is finalized.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `invoice` | path | string | Yes | Invoice ID of line item |
| `line_item_id` | path | string | Yes | Invoice line item ID |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[line_item](../schemas/line/line-item.md)

