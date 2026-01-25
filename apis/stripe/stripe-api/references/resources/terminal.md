# terminal

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v1/terminal/configurations` | List all Configurations | [View](../operations/GetTerminalConfigurations.md) |
| POST | `/v1/terminal/configurations` | Create a Configuration | [View](../operations/PostTerminalConfigurations.md) |
| GET | `/v1/terminal/configurations/{configuration}` | Retrieve a Configuration | [View](../operations/GetTerminalConfigurationsConfiguration.md) |
| POST | `/v1/terminal/configurations/{configuration}` | Update a Configuration | [View](../operations/PostTerminalConfigurationsConfiguration.md) |
| DELETE | `/v1/terminal/configurations/{configuration}` | Delete a Configuration | [View](../operations/DeleteTerminalConfigurationsConfiguration.md) |
| POST | `/v1/terminal/connection_tokens` | Create a Connection Token | [View](../operations/PostTerminalConnectionTokens.md) |
| GET | `/v1/terminal/locations` | List all Locations | [View](../operations/GetTerminalLocations.md) |
| POST | `/v1/terminal/locations` | Create a Location | [View](../operations/PostTerminalLocations.md) |
| GET | `/v1/terminal/locations/{location}` | Retrieve a Location | [View](../operations/GetTerminalLocationsLocation.md) |
| POST | `/v1/terminal/locations/{location}` | Update a Location | [View](../operations/PostTerminalLocationsLocation.md) |
| DELETE | `/v1/terminal/locations/{location}` | Delete a Location | [View](../operations/DeleteTerminalLocationsLocation.md) |
| POST | `/v1/terminal/onboarding_links` | Create an Onboarding Link | [View](../operations/PostTerminalOnboardingLinks.md) |
| GET | `/v1/terminal/readers` | List all Readers | [View](../operations/GetTerminalReaders.md) |
| POST | `/v1/terminal/readers` | Create a Reader | [View](../operations/PostTerminalReaders.md) |
| GET | `/v1/terminal/readers/{reader}` | Retrieve a Reader | [View](../operations/GetTerminalReadersReader.md) |
| POST | `/v1/terminal/readers/{reader}` | Update a Reader | [View](../operations/PostTerminalReadersReader.md) |
| DELETE | `/v1/terminal/readers/{reader}` | Delete a Reader | [View](../operations/DeleteTerminalReadersReader.md) |
| POST | `/v1/terminal/readers/{reader}/cancel_action` | Cancel the current reader action | [View](../operations/PostTerminalReadersReaderCancelAction.md) |
| POST | `/v1/terminal/readers/{reader}/collect_inputs` | Collect inputs using a Reader | [View](../operations/PostTerminalReadersReaderCollectInputs.md) |
| POST | `/v1/terminal/readers/{reader}/collect_payment_method` | Hand off a PaymentIntent to a Reader and collect card details | [View](../operations/PostTerminalReadersReaderCollectPaymentMethod.md) |
| POST | `/v1/terminal/readers/{reader}/confirm_payment_intent` | Confirm a PaymentIntent on the Reader | [View](../operations/PostTerminalReadersReaderConfirmPaymentIntent.md) |
| POST | `/v1/terminal/readers/{reader}/process_payment_intent` | Hand-off a PaymentIntent to a Reader | [View](../operations/PostTerminalReadersReaderProcessPaymentIntent.md) |
| POST | `/v1/terminal/readers/{reader}/process_setup_intent` | Hand-off a SetupIntent to a Reader | [View](../operations/PostTerminalReadersReaderProcessSetupIntent.md) |
| POST | `/v1/terminal/readers/{reader}/refund_payment` | Refund a Charge or a PaymentIntent in-person | [View](../operations/PostTerminalReadersReaderRefundPayment.md) |
| POST | `/v1/terminal/readers/{reader}/set_reader_display` | Set reader display | [View](../operations/PostTerminalReadersReaderSetReaderDisplay.md) |
