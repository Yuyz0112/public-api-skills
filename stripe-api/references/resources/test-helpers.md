# test_helpers

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/v1/test_helpers/confirmation_tokens` | Create a test Confirmation Token | [View](../operations/PostTestHelpersConfirmationTokens.md) |
| POST | `/v1/test_helpers/customers/{customer}/fund_cash_balance` | Fund a test mode cash balance | [View](../operations/PostTestHelpersCustomersCustomerFundCashBalance.md) |
| POST | `/v1/test_helpers/issuing/authorizations` | Create a test-mode authorization | [View](../operations/PostTestHelpersIssuingAuthorizations.md) |
| POST | `/v1/test_helpers/issuing/authorizations/{authorization}/capture` | Capture a test-mode authorization | [View](../operations/PostTestHelpersIssuingAuthorizationsAuthorizationCapture.md) |
| POST | `/v1/test_helpers/issuing/authorizations/{authorization}/expire` | Expire a test-mode authorization | [View](../operations/PostTestHelpersIssuingAuthorizationsAuthorizationExpire.md) |
| POST | `/v1/test_helpers/issuing/authorizations/{authorization}/finalize_amount` | Finalize a test-mode authorization's amount | [View](../operations/PostTestHelpersIssuingAuthorizationsAuthorizationFinalizeAmount.md) |
| POST | `/v1/test_helpers/issuing/authorizations/{authorization}/fraud_challenges/respond` | Respond to fraud challenge | [View](../operations/PostTestHelpersIssuingAuthorizationsAuthorizationFraudChallengesRespond.md) |
| POST | `/v1/test_helpers/issuing/authorizations/{authorization}/increment` | Increment a test-mode authorization | [View](../operations/PostTestHelpersIssuingAuthorizationsAuthorizationIncrement.md) |
| POST | `/v1/test_helpers/issuing/authorizations/{authorization}/reverse` | Reverse a test-mode authorization | [View](../operations/PostTestHelpersIssuingAuthorizationsAuthorizationReverse.md) |
| POST | `/v1/test_helpers/issuing/cards/{card}/shipping/deliver` | Deliver a testmode card | [View](../operations/PostTestHelpersIssuingCardsCardShippingDeliver.md) |
| POST | `/v1/test_helpers/issuing/cards/{card}/shipping/fail` | Fail a testmode card | [View](../operations/PostTestHelpersIssuingCardsCardShippingFail.md) |
| POST | `/v1/test_helpers/issuing/cards/{card}/shipping/return` | Return a testmode card | [View](../operations/PostTestHelpersIssuingCardsCardShippingReturn.md) |
| POST | `/v1/test_helpers/issuing/cards/{card}/shipping/ship` | Ship a testmode card | [View](../operations/PostTestHelpersIssuingCardsCardShippingShip.md) |
| POST | `/v1/test_helpers/issuing/cards/{card}/shipping/submit` | Submit a testmode card | [View](../operations/PostTestHelpersIssuingCardsCardShippingSubmit.md) |
| POST | `/v1/test_helpers/issuing/personalization_designs/{personalization_design}/activate` | Activate a testmode personalization design | [View](../operations/PostTestHelpersIssuingPersonalizationDesignsPersonalizationDesignActivate.md) |
| POST | `/v1/test_helpers/issuing/personalization_designs/{personalization_design}/deactivate` | Deactivate a testmode personalization design | [View](../operations/PostTestHelpersIssuingPersonalizationDesignsPersonalizationDesignDeactivate.md) |
| POST | `/v1/test_helpers/issuing/personalization_designs/{personalization_design}/reject` | Reject a testmode personalization design | [View](../operations/PostTestHelpersIssuingPersonalizationDesignsPersonalizationDesignReject.md) |
| POST | `/v1/test_helpers/issuing/settlements` | Create a test-mode settlement | [View](../operations/PostTestHelpersIssuingSettlements.md) |
| POST | `/v1/test_helpers/issuing/settlements/{settlement}/complete` | Complete a test-mode settlement | [View](../operations/PostTestHelpersIssuingSettlementsSettlementComplete.md) |
| POST | `/v1/test_helpers/issuing/transactions/create_force_capture` | Create a test-mode force capture | [View](../operations/PostTestHelpersIssuingTransactionsCreateForceCapture.md) |
| POST | `/v1/test_helpers/issuing/transactions/create_unlinked_refund` | Create a test-mode unlinked refund | [View](../operations/PostTestHelpersIssuingTransactionsCreateUnlinkedRefund.md) |
| POST | `/v1/test_helpers/issuing/transactions/{transaction}/refund` | Refund a test-mode transaction | [View](../operations/PostTestHelpersIssuingTransactionsTransactionRefund.md) |
| POST | `/v1/test_helpers/refunds/{refund}/expire` | Expire a pending refund. | [View](../operations/PostTestHelpersRefundsRefundExpire.md) |
| POST | `/v1/test_helpers/terminal/readers/{reader}/present_payment_method` | Simulate presenting a payment method | [View](../operations/PostTestHelpersTerminalReadersReaderPresentPaymentMethod.md) |
| POST | `/v1/test_helpers/terminal/readers/{reader}/succeed_input_collection` | Simulate a successful input collection | [View](../operations/PostTestHelpersTerminalReadersReaderSucceedInputCollection.md) |
| POST | `/v1/test_helpers/terminal/readers/{reader}/timeout_input_collection` | Simulate an input collection timeout | [View](../operations/PostTestHelpersTerminalReadersReaderTimeoutInputCollection.md) |
| GET | `/v1/test_helpers/test_clocks` | List all test clocks | [View](../operations/GetTestHelpersTestClocks.md) |
| POST | `/v1/test_helpers/test_clocks` | Create a test clock | [View](../operations/PostTestHelpersTestClocks.md) |
| GET | `/v1/test_helpers/test_clocks/{test_clock}` | Retrieve a test clock | [View](../operations/GetTestHelpersTestClocksTestClock.md) |
| DELETE | `/v1/test_helpers/test_clocks/{test_clock}` | Delete a test clock | [View](../operations/DeleteTestHelpersTestClocksTestClock.md) |
| POST | `/v1/test_helpers/test_clocks/{test_clock}/advance` | Advance a test clock | [View](../operations/PostTestHelpersTestClocksTestClockAdvance.md) |
| POST | `/v1/test_helpers/treasury/inbound_transfers/{id}/fail` | Test mode: Fail an InboundTransfer | [View](../operations/PostTestHelpersTreasuryInboundTransfersIdFail.md) |
| POST | `/v1/test_helpers/treasury/inbound_transfers/{id}/return` | Test mode: Return an InboundTransfer | [View](../operations/PostTestHelpersTreasuryInboundTransfersIdReturn.md) |
| POST | `/v1/test_helpers/treasury/inbound_transfers/{id}/succeed` | Test mode: Succeed an InboundTransfer | [View](../operations/PostTestHelpersTreasuryInboundTransfersIdSucceed.md) |
| POST | `/v1/test_helpers/treasury/outbound_payments/{id}` | Test mode: Update an OutboundPayment | [View](../operations/PostTestHelpersTreasuryOutboundPaymentsId.md) |
| POST | `/v1/test_helpers/treasury/outbound_payments/{id}/fail` | Test mode: Fail an OutboundPayment | [View](../operations/PostTestHelpersTreasuryOutboundPaymentsIdFail.md) |
| POST | `/v1/test_helpers/treasury/outbound_payments/{id}/post` | Test mode: Post an OutboundPayment | [View](../operations/PostTestHelpersTreasuryOutboundPaymentsIdPost.md) |
| POST | `/v1/test_helpers/treasury/outbound_payments/{id}/return` | Test mode: Return an OutboundPayment | [View](../operations/PostTestHelpersTreasuryOutboundPaymentsIdReturn.md) |
| POST | `/v1/test_helpers/treasury/outbound_transfers/{outbound_transfer}` | Test mode: Update an OutboundTransfer | [View](../operations/PostTestHelpersTreasuryOutboundTransfersOutboundTransfer.md) |
| POST | `/v1/test_helpers/treasury/outbound_transfers/{outbound_transfer}/fail` | Test mode: Fail an OutboundTransfer | [View](../operations/PostTestHelpersTreasuryOutboundTransfersOutboundTransferFail.md) |
| POST | `/v1/test_helpers/treasury/outbound_transfers/{outbound_transfer}/post` | Test mode: Post an OutboundTransfer | [View](../operations/PostTestHelpersTreasuryOutboundTransfersOutboundTransferPost.md) |
| POST | `/v1/test_helpers/treasury/outbound_transfers/{outbound_transfer}/return` | Test mode: Return an OutboundTransfer | [View](../operations/PostTestHelpersTreasuryOutboundTransfersOutboundTransferReturn.md) |
| POST | `/v1/test_helpers/treasury/received_credits` | Test mode: Create a ReceivedCredit | [View](../operations/PostTestHelpersTreasuryReceivedCredits.md) |
| POST | `/v1/test_helpers/treasury/received_debits` | Test mode: Create a ReceivedDebit | [View](../operations/PostTestHelpersTreasuryReceivedDebits.md) |
