# abuse-reports Schemas

58 schemas in this group.

| Schema | Type | Description |
|--------|------|-------------|
| [abuse-reports_AbuseReport](abuse-reports-AbuseReport.md) | object |  |
| [abuse-reports_AppealReason](abuse-reports-AppealReason.md) | enum | Reason why the customer is appealing. |
| [abuse-reports_BadActError](abuse-reports-BadActError.md) | primitive | Report has invalid type |
| [abuse-reports_BadAddressError](abuse-reports-BadAddressError.md) | primitive | Provided value has invalid size |
| [abuse-reports_BadAgentNameError](abuse-reports-BadAgentNameError.md) | primitive | Provided value has invalid size |
| [abuse-reports_BadCityError](abuse-reports-BadCityError.md) | primitive | Provided value has invalid size |
| [abuse-reports_BadCommentsError](abuse-reports-BadCommentsError.md) | primitive | Comment maximum length of 2000 characters exceeded |
| [abuse-reports_BadCountryError](abuse-reports-BadCountryError.md) | primitive | Provided value has invalid size |
| [abuse-reports_BadEmailError](abuse-reports-BadEmailError.md) | primitive | Provided email was invalid |
| [abuse-reports_BadIPError](abuse-reports-BadIPError.md) | primitive | Invalid IP passed to api |
| [abuse-reports_BadJustError](abuse-reports-BadJustError.md) | primitive | Please provide a more detailed description of the  |
| [abuse-reports_BadNameError](abuse-reports-BadNameError.md) | primitive | Missing a required field |
| [abuse-reports_BadPortsProtocolError](abuse-reports-BadPortsProtocolError.md) | primitive | Invalid Port and Protocol passed to api |
| [abuse-reports_BadStateError](abuse-reports-BadStateError.md) | primitive | Provided value has invalid size |
| [abuse-reports_BadUrlsError](abuse-reports-BadUrlsError.md) | primitive | Invalid URL (http://example.com/) Invalid URL Sche |
| [abuse-reports_BaseReportFields](abuse-reports-BaseReportFields.md) | object |  |
| [abuse-reports_CSAMReport](abuse-reports-CSAMReport.md) | allOf |  |
| [abuse-reports_DBError](abuse-reports-DBError.md) | primitive | Failed while reading from database Failed while wr |
| [abuse-reports_DMCAReport](abuse-reports-DMCAReport.md) | allOf |  |
| [abuse-reports_DedupeError](abuse-reports-DedupeError.md) | primitive | You have already submitted this URL in the last 7  |
| [abuse-reports_DiffEmailError](abuse-reports-DiffEmailError.md) | primitive | Provided emails did not match |
| [abuse-reports_EmailError](abuse-reports-EmailError.md) | primitive | Failed to send confirmation email |
| [abuse-reports_ErrorCode](abuse-reports-ErrorCode.md) | oneOf |  |
| [abuse-reports_ErrorMessage](abuse-reports-ErrorMessage.md) | object |  |
| [abuse-reports_GeneralReport](abuse-reports-GeneralReport.md) | allOf |  |
| [abuse-reports_InternalError](abuse-reports-InternalError.md) | primitive | Failed to translate email |
| [abuse-reports_InvalidNotifyError](abuse-reports-InvalidNotifyError.md) | primitive | Invalid value for notification preference |
| [abuse-reports_MaxIPsError](abuse-reports-MaxIPsError.md) | primitive | Provided value has invalid size |
| [abuse-reports_Message](abuse-reports-Message.md) | object |  |
| [abuse-reports_MitigatedEntityType](abuse-reports-MitigatedEntityType.md) | enum |  |
| [abuse-reports_MitigationAppeal](abuse-reports-MitigationAppeal.md) | object |  |
| [abuse-reports_MitigationAppealRequest](abuse-reports-MitigationAppealRequest.md) | object |  |
| [abuse-reports_MitigationAppealResult](abuse-reports-MitigationAppealResult.md) | object |  |
| [abuse-reports_MitigationListItem](abuse-reports-MitigationListItem.md) | object |  |
| [abuse-reports_MitigationStatus](abuse-reports-MitigationStatus.md) | enum | The status of a mitigation |
| [abuse-reports_MitigationSummary](abuse-reports-MitigationSummary.md) | object | A summary of the mitigations related to this repor |
| [abuse-reports_MitigationType](abuse-reports-MitigationType.md) | enum | The type of mitigation |
| [abuse-reports_MustNotifyError](abuse-reports-MustNotifyError.md) | primitive | Please pick one party to notify about this report |
| [abuse-reports_NCSEIReport](abuse-reports-NCSEIReport.md) | allOf |  |
| [abuse-reports_NoAgreeError](abuse-reports-NoAgreeError.md) | primitive | Must acknowledge that you are bound by 512(f), tha |
| [abuse-reports_NoOriginalWorkError](abuse-reports-NoOriginalWorkError.md) | primitive | Original Work section must be between 1 and 2000 c |
| [abuse-reports_NoSigError](abuse-reports-NoSigError.md) | primitive | Signature must match your name |
| [abuse-reports_PhishingReport](abuse-reports-PhishingReport.md) | allOf |  |
| [abuse-reports_PortsProtocolError](abuse-reports-PortsProtocolError.md) | primitive | Provided value has invalid size |
| [abuse-reports_RegistrarWhoisReport](abuse-reports-RegistrarWhoisReport.md) | allOf |  |
| [abuse-reports_ReportStatus](abuse-reports-ReportStatus.md) | enum | An enum value that represents the status of an abu |
| [abuse-reports_ReportType](abuse-reports-ReportType.md) | enum | The abuse report type |
| [abuse-reports_SubmissionReportType](abuse-reports-SubmissionReportType.md) | primitive | The report type for submitted reports. |
| [abuse-reports_SubmitErrorResponse](abuse-reports-SubmitErrorResponse.md) | object |  |
| [abuse-reports_SubmitReportRequest](abuse-reports-SubmitReportRequest.md) | oneOf |  |
| [abuse-reports_SubmitReportResponse](abuse-reports-SubmitReportResponse.md) | object |  |
| [abuse-reports_SubmitterDetails](abuse-reports-SubmitterDetails.md) | object | Information about the submitter of the report. |
| [abuse-reports_ThreatReport](abuse-reports-ThreatReport.md) | allOf |  |
| [abuse-reports_TrademarkReport](abuse-reports-TrademarkReport.md) | allOf |  |
| [abuse-reports_UnexpectedActError](abuse-reports-UnexpectedActError.md) | primitive | Report has the wrong type |
| [abuse-reports_UnknownError](abuse-reports-UnknownError.md) | primitive | An unexpected error occurred |
| [abuse-reports_UrlNotOrangeError](abuse-reports-UrlNotOrangeError.md) | primitive | A URL contains a domain that is not active on Clou |
| [abuse-reports_UrlNotvalidError](abuse-reports-UrlNotvalidError.md) | primitive | You have entered URLs that contain more than 1 uni |
