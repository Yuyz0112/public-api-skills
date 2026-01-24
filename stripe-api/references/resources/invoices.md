# invoices

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v1/invoices` | List all invoices | [View](../operations/getinvoices.md) |
| POST | `/v1/invoices` | Create an invoice | [View](../operations/postinvoices.md) |
| POST | `/v1/invoices/create_preview` | Create a preview invoice | [View](../operations/postinvoicescreatepreview.md) |
| GET | `/v1/invoices/search` | Search invoices | [View](../operations/getinvoicessearch.md) |
| GET | `/v1/invoices/{invoice}` | Retrieve an invoice | [View](../operations/getinvoicesinvoice.md) |
| POST | `/v1/invoices/{invoice}` | Update an invoice | [View](../operations/postinvoicesinvoice.md) |
| DELETE | `/v1/invoices/{invoice}` | Delete a draft invoice | [View](../operations/deleteinvoicesinvoice.md) |
| POST | `/v1/invoices/{invoice}/add_lines` | Bulk add invoice line items | [View](../operations/postinvoicesinvoiceaddlines.md) |
| POST | `/v1/invoices/{invoice}/attach_payment` | Attach a payment to an Invoice | [View](../operations/postinvoicesinvoiceattachpayment.md) |
| POST | `/v1/invoices/{invoice}/finalize` | Finalize an invoice | [View](../operations/postinvoicesinvoicefinalize.md) |
| GET | `/v1/invoices/{invoice}/lines` | Retrieve an invoice's line items | [View](../operations/getinvoicesinvoicelines.md) |
| POST | `/v1/invoices/{invoice}/lines/{line_item_id}` | Update an invoice's line item | [View](../operations/postinvoicesinvoicelineslineitemid.md) |
| POST | `/v1/invoices/{invoice}/mark_uncollectible` | Mark an invoice as uncollectible | [View](../operations/postinvoicesinvoicemarkuncollectible.md) |
| POST | `/v1/invoices/{invoice}/pay` | Pay an invoice | [View](../operations/postinvoicesinvoicepay.md) |
| POST | `/v1/invoices/{invoice}/remove_lines` | Bulk remove invoice line items | [View](../operations/postinvoicesinvoiceremovelines.md) |
| POST | `/v1/invoices/{invoice}/send` | Send an invoice for manual payment | [View](../operations/postinvoicesinvoicesend.md) |
| POST | `/v1/invoices/{invoice}/update_lines` | Bulk update invoice line items | [View](../operations/postinvoicesinvoiceupdatelines.md) |
| POST | `/v1/invoices/{invoice}/void` | Void an invoice | [View](../operations/postinvoicesinvoicevoid.md) |
