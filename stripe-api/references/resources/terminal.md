# terminal

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v1/terminal/configurations` | List all Configurations | [View](../operations/getterminalconfigurations.md) |
| POST | `/v1/terminal/configurations` | Create a Configuration | [View](../operations/postterminalconfigurations.md) |
| GET | `/v1/terminal/configurations/{configuration}` | Retrieve a Configuration | [View](../operations/getterminalconfigurationsconfiguration.md) |
| POST | `/v1/terminal/configurations/{configuration}` | Update a Configuration | [View](../operations/postterminalconfigurationsconfiguration.md) |
| DELETE | `/v1/terminal/configurations/{configuration}` | Delete a Configuration | [View](../operations/deleteterminalconfigurationsconfiguration.md) |
| POST | `/v1/terminal/connection_tokens` | Create a Connection Token | [View](../operations/postterminalconnectiontokens.md) |
| GET | `/v1/terminal/locations` | List all Locations | [View](../operations/getterminallocations.md) |
| POST | `/v1/terminal/locations` | Create a Location | [View](../operations/postterminallocations.md) |
| GET | `/v1/terminal/locations/{location}` | Retrieve a Location | [View](../operations/getterminallocationslocation.md) |
| POST | `/v1/terminal/locations/{location}` | Update a Location | [View](../operations/postterminallocationslocation.md) |
| DELETE | `/v1/terminal/locations/{location}` | Delete a Location | [View](../operations/deleteterminallocationslocation.md) |
| POST | `/v1/terminal/onboarding_links` | Create an Onboarding Link | [View](../operations/postterminalonboardinglinks.md) |
| GET | `/v1/terminal/readers` | List all Readers | [View](../operations/getterminalreaders.md) |
| POST | `/v1/terminal/readers` | Create a Reader | [View](../operations/postterminalreaders.md) |
| GET | `/v1/terminal/readers/{reader}` | Retrieve a Reader | [View](../operations/getterminalreadersreader.md) |
| POST | `/v1/terminal/readers/{reader}` | Update a Reader | [View](../operations/postterminalreadersreader.md) |
| DELETE | `/v1/terminal/readers/{reader}` | Delete a Reader | [View](../operations/deleteterminalreadersreader.md) |
| POST | `/v1/terminal/readers/{reader}/cancel_action` | Cancel the current reader action | [View](../operations/postterminalreadersreadercancelaction.md) |
| POST | `/v1/terminal/readers/{reader}/collect_inputs` | Collect inputs using a Reader | [View](../operations/postterminalreadersreadercollectinputs.md) |
| POST | `/v1/terminal/readers/{reader}/collect_payment_method` | Hand off a PaymentIntent to a Reader and collect card details | [View](../operations/postterminalreadersreadercollectpaymentmethod.md) |
| POST | `/v1/terminal/readers/{reader}/confirm_payment_intent` | Confirm a PaymentIntent on the Reader | [View](../operations/postterminalreadersreaderconfirmpaymentintent.md) |
| POST | `/v1/terminal/readers/{reader}/process_payment_intent` | Hand-off a PaymentIntent to a Reader | [View](../operations/postterminalreadersreaderprocesspaymentintent.md) |
| POST | `/v1/terminal/readers/{reader}/process_setup_intent` | Hand-off a SetupIntent to a Reader | [View](../operations/postterminalreadersreaderprocesssetupintent.md) |
| POST | `/v1/terminal/readers/{reader}/refund_payment` | Refund a Charge or a PaymentIntent in-person | [View](../operations/postterminalreadersreaderrefundpayment.md) |
| POST | `/v1/terminal/readers/{reader}/set_reader_display` | Set reader display | [View](../operations/postterminalreadersreadersetreaderdisplay.md) |
