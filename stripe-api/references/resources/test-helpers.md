# test_helpers

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/v1/test_helpers/confirmation_tokens` | Create a test Confirmation Token | [View](../operations/posttesthelpersconfirmationtokens.md) |
| POST | `/v1/test_helpers/customers/{customer}/fund_cash_balance` | Fund a test mode cash balance | [View](../operations/posttesthelperscustomerscustomerfundcashbalance.md) |
| POST | `/v1/test_helpers/issuing/authorizations` | Create a test-mode authorization | [View](../operations/posttesthelpersissuingauthorizations.md) |
| POST | `/v1/test_helpers/issuing/authorizations/{authorization}/capture` | Capture a test-mode authorization | [View](../operations/posttesthelpersissuingauthorizationsauthorizationcapture.md) |
| POST | `/v1/test_helpers/issuing/authorizations/{authorization}/expire` | Expire a test-mode authorization | [View](../operations/posttesthelpersissuingauthorizationsauthorizationexpire.md) |
| POST | `/v1/test_helpers/issuing/authorizations/{authorization}/finalize_amount` | Finalize a test-mode authorization's amount | [View](../operations/posttesthelpersissuingauthorizationsauthorizationfinalizeamount.md) |
| POST | `/v1/test_helpers/issuing/authorizations/{authorization}/fraud_challenges/respond` | Respond to fraud challenge | [View](../operations/posttesthelpersissuingauthorizationsauthorizationfraudchallengesrespond.md) |
| POST | `/v1/test_helpers/issuing/authorizations/{authorization}/increment` | Increment a test-mode authorization | [View](../operations/posttesthelpersissuingauthorizationsauthorizationincrement.md) |
| POST | `/v1/test_helpers/issuing/authorizations/{authorization}/reverse` | Reverse a test-mode authorization | [View](../operations/posttesthelpersissuingauthorizationsauthorizationreverse.md) |
| POST | `/v1/test_helpers/issuing/cards/{card}/shipping/deliver` | Deliver a testmode card | [View](../operations/posttesthelpersissuingcardscardshippingdeliver.md) |
| POST | `/v1/test_helpers/issuing/cards/{card}/shipping/fail` | Fail a testmode card | [View](../operations/posttesthelpersissuingcardscardshippingfail.md) |
| POST | `/v1/test_helpers/issuing/cards/{card}/shipping/return` | Return a testmode card | [View](../operations/posttesthelpersissuingcardscardshippingreturn.md) |
| POST | `/v1/test_helpers/issuing/cards/{card}/shipping/ship` | Ship a testmode card | [View](../operations/posttesthelpersissuingcardscardshippingship.md) |
| POST | `/v1/test_helpers/issuing/cards/{card}/shipping/submit` | Submit a testmode card | [View](../operations/posttesthelpersissuingcardscardshippingsubmit.md) |
| POST | `/v1/test_helpers/issuing/personalization_designs/{personalization_design}/activate` | Activate a testmode personalization design | [View](../operations/posttesthelpersissuingpersonalizationdesignspersonalizationdesignactivate.md) |
| POST | `/v1/test_helpers/issuing/personalization_designs/{personalization_design}/deactivate` | Deactivate a testmode personalization design | [View](../operations/posttesthelpersissuingpersonalizationdesignspersonalizationdesigndeactivate.md) |
| POST | `/v1/test_helpers/issuing/personalization_designs/{personalization_design}/reject` | Reject a testmode personalization design | [View](../operations/posttesthelpersissuingpersonalizationdesignspersonalizationdesignreject.md) |
| POST | `/v1/test_helpers/issuing/settlements` | Create a test-mode settlement | [View](../operations/posttesthelpersissuingsettlements.md) |
| POST | `/v1/test_helpers/issuing/settlements/{settlement}/complete` | Complete a test-mode settlement | [View](../operations/posttesthelpersissuingsettlementssettlementcomplete.md) |
| POST | `/v1/test_helpers/issuing/transactions/create_force_capture` | Create a test-mode force capture | [View](../operations/posttesthelpersissuingtransactionscreateforcecapture.md) |
| POST | `/v1/test_helpers/issuing/transactions/create_unlinked_refund` | Create a test-mode unlinked refund | [View](../operations/posttesthelpersissuingtransactionscreateunlinkedrefund.md) |
| POST | `/v1/test_helpers/issuing/transactions/{transaction}/refund` | Refund a test-mode transaction | [View](../operations/posttesthelpersissuingtransactionstransactionrefund.md) |
| POST | `/v1/test_helpers/refunds/{refund}/expire` | Expire a pending refund. | [View](../operations/posttesthelpersrefundsrefundexpire.md) |
| POST | `/v1/test_helpers/terminal/readers/{reader}/present_payment_method` | Simulate presenting a payment method | [View](../operations/posttesthelpersterminalreadersreaderpresentpaymentmethod.md) |
| POST | `/v1/test_helpers/terminal/readers/{reader}/succeed_input_collection` | Simulate a successful input collection | [View](../operations/posttesthelpersterminalreadersreadersucceedinputcollection.md) |
| POST | `/v1/test_helpers/terminal/readers/{reader}/timeout_input_collection` | Simulate an input collection timeout | [View](../operations/posttesthelpersterminalreadersreadertimeoutinputcollection.md) |
| GET | `/v1/test_helpers/test_clocks` | List all test clocks | [View](../operations/gettesthelperstestclocks.md) |
| POST | `/v1/test_helpers/test_clocks` | Create a test clock | [View](../operations/posttesthelperstestclocks.md) |
| GET | `/v1/test_helpers/test_clocks/{test_clock}` | Retrieve a test clock | [View](../operations/gettesthelperstestclockstestclock.md) |
| DELETE | `/v1/test_helpers/test_clocks/{test_clock}` | Delete a test clock | [View](../operations/deletetesthelperstestclockstestclock.md) |
| POST | `/v1/test_helpers/test_clocks/{test_clock}/advance` | Advance a test clock | [View](../operations/posttesthelperstestclockstestclockadvance.md) |
| POST | `/v1/test_helpers/treasury/inbound_transfers/{id}/fail` | Test mode: Fail an InboundTransfer | [View](../operations/posttesthelperstreasuryinboundtransfersidfail.md) |
| POST | `/v1/test_helpers/treasury/inbound_transfers/{id}/return` | Test mode: Return an InboundTransfer | [View](../operations/posttesthelperstreasuryinboundtransfersidreturn.md) |
| POST | `/v1/test_helpers/treasury/inbound_transfers/{id}/succeed` | Test mode: Succeed an InboundTransfer | [View](../operations/posttesthelperstreasuryinboundtransfersidsucceed.md) |
| POST | `/v1/test_helpers/treasury/outbound_payments/{id}` | Test mode: Update an OutboundPayment | [View](../operations/posttesthelperstreasuryoutboundpaymentsid.md) |
| POST | `/v1/test_helpers/treasury/outbound_payments/{id}/fail` | Test mode: Fail an OutboundPayment | [View](../operations/posttesthelperstreasuryoutboundpaymentsidfail.md) |
| POST | `/v1/test_helpers/treasury/outbound_payments/{id}/post` | Test mode: Post an OutboundPayment | [View](../operations/posttesthelperstreasuryoutboundpaymentsidpost.md) |
| POST | `/v1/test_helpers/treasury/outbound_payments/{id}/return` | Test mode: Return an OutboundPayment | [View](../operations/posttesthelperstreasuryoutboundpaymentsidreturn.md) |
| POST | `/v1/test_helpers/treasury/outbound_transfers/{outbound_transfer}` | Test mode: Update an OutboundTransfer | [View](../operations/posttesthelperstreasuryoutboundtransfersoutboundtransfer.md) |
| POST | `/v1/test_helpers/treasury/outbound_transfers/{outbound_transfer}/fail` | Test mode: Fail an OutboundTransfer | [View](../operations/posttesthelperstreasuryoutboundtransfersoutboundtransferfail.md) |
| POST | `/v1/test_helpers/treasury/outbound_transfers/{outbound_transfer}/post` | Test mode: Post an OutboundTransfer | [View](../operations/posttesthelperstreasuryoutboundtransfersoutboundtransferpost.md) |
| POST | `/v1/test_helpers/treasury/outbound_transfers/{outbound_transfer}/return` | Test mode: Return an OutboundTransfer | [View](../operations/posttesthelperstreasuryoutboundtransfersoutboundtransferreturn.md) |
| POST | `/v1/test_helpers/treasury/received_credits` | Test mode: Create a ReceivedCredit | [View](../operations/posttesthelperstreasuryreceivedcredits.md) |
| POST | `/v1/test_helpers/treasury/received_debits` | Test mode: Create a ReceivedDebit | [View](../operations/posttesthelperstreasuryreceiveddebits.md) |
