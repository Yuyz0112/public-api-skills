# invoices

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v1/invoices` | List all invoices | [View](../operations/GetInvoices.md) |
| POST | `/v1/invoices` | Create an invoice | [View](../operations/PostInvoices.md) |
| POST | `/v1/invoices/create_preview` | Create a preview invoice | [View](../operations/PostInvoicesCreatePreview.md) |
| GET | `/v1/invoices/search` | Search invoices | [View](../operations/GetInvoicesSearch.md) |
| GET | `/v1/invoices/{invoice}` | Retrieve an invoice | [View](../operations/GetInvoicesInvoice.md) |
| POST | `/v1/invoices/{invoice}` | Update an invoice | [View](../operations/PostInvoicesInvoice.md) |
| DELETE | `/v1/invoices/{invoice}` | Delete a draft invoice | [View](../operations/DeleteInvoicesInvoice.md) |
| POST | `/v1/invoices/{invoice}/add_lines` | Bulk add invoice line items | [View](../operations/PostInvoicesInvoiceAddLines.md) |
| POST | `/v1/invoices/{invoice}/attach_payment` | Attach a payment to an Invoice | [View](../operations/PostInvoicesInvoiceAttachPayment.md) |
| POST | `/v1/invoices/{invoice}/finalize` | Finalize an invoice | [View](../operations/PostInvoicesInvoiceFinalize.md) |
| GET | `/v1/invoices/{invoice}/lines` | Retrieve an invoice's line items | [View](../operations/GetInvoicesInvoiceLines.md) |
| POST | `/v1/invoices/{invoice}/lines/{line_item_id}` | Update an invoice's line item | [View](../operations/PostInvoicesInvoiceLinesLineItemId.md) |
| POST | `/v1/invoices/{invoice}/mark_uncollectible` | Mark an invoice as uncollectible | [View](../operations/PostInvoicesInvoiceMarkUncollectible.md) |
| POST | `/v1/invoices/{invoice}/pay` | Pay an invoice | [View](../operations/PostInvoicesInvoicePay.md) |
| POST | `/v1/invoices/{invoice}/remove_lines` | Bulk remove invoice line items | [View](../operations/PostInvoicesInvoiceRemoveLines.md) |
| POST | `/v1/invoices/{invoice}/send` | Send an invoice for manual payment | [View](../operations/PostInvoicesInvoiceSend.md) |
| POST | `/v1/invoices/{invoice}/update_lines` | Bulk update invoice line items | [View](../operations/PostInvoicesInvoiceUpdateLines.md) |
| POST | `/v1/invoices/{invoice}/void` | Void an invoice | [View](../operations/PostInvoicesInvoiceVoid.md) |
