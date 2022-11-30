# Power App Documentation \- Building Access

| Property                   | Value                                   |
| -------------------------- | --------------------------------------- |
| App Name                   | Building Access                         |
| App Logo                   | ![App Logo](resources/appLogoSmall.png) |
| Documentation generated at | Wednesday, 30 November 2022 10:07 am    |

- [Overview](index-Building-Access.md)
- [App Details](appdetails-Building-Access.md)
- [Variables](variables-Building-Access.md)
- [DataSources](datasources-Building-Access.md)
- [Resources](resources-Building-Access.md)
- [Controls](controls-Building-Access.md)

## Variables & Collections

There are 30 Global Variables, 0 Context Variables and 39 Collections.

### Global Variables

#### isNavigatedFromApprovalsScreen

Variable used in:

| Control                                                                                                        | Property |
| -------------------------------------------------------------------------------------------------------------- | -------- |
| [btnCancelRequest (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#btncancelrequest)     | OnSelect |
| [btnRejectRequest (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#btnrejectrequest)     | OnSelect |
| [btnRejectSelected (Approval Screen)](screen-Approval-Screen-Building-Access.md#btnrejectselected)             | OnSelect |
| [btnRequestReject (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btnrequestreject) | OnSelect |

#### locRowGUID

Variable used in:

| Control                                                                                      | Property |
| -------------------------------------------------------------------------------------------- | -------- |
| [icnNextArrow (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#icnnextarrow) | OnSelect |

#### locRowId

Variable used in:

| Control                                                                                      | Property |
| -------------------------------------------------------------------------------------------- | -------- |
| [icnNextArrow (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#icnnextarrow) | OnSelect |

#### varAppSettings

Variable used in:

| Control                                                                                                                                             | Property    |
| --------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| [App ()](screen--Building-Access.md#app)                                                                                                            | OnStart     |
| [btnBackBuildingScreen (Building Screen)](screen-Building-Screen-Building-Access.md#btnbackbuildingscreen)                                          | OnSelect    |
| [btnCheckAvailability (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#btncheckavailability)                                        | DisplayMode |
| [btnCheckIn (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckin)                                            | OnSelect    |
| [btnSave&NextDateScreen (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#btnsave&nextdatescreen)                                    | DisplayMode |
| [btnSaveKeyQuestions\_1 (My Request List Screen)](screen-My-Request-List-Screen-Building-Access.md#btnsavekeyquestions_1)                           | OnSelect    |
| [chkSelectRequest (Approval Screen)](screen-Approval-Screen-Building-Access.md#chkselectrequest)                                                    | DisplayMode |
| [chkSetDefaultApprover (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#chksetdefaultapprover)                            | Visible     |
| [datepkEndDate (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#datepkenddate)                                                      | OnChange    |
| [datepkStartDate (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#datepkstartdate)                                                  | OnChange    |
| [Home Screen (Home Screen)](screen-Home-Screen-Building-Access.md#home-screen)                                                                      | OnVisible   |
| [htmlErrorMessage\_KeyquestionsScreens (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#htmlerrormessage_keyquestionsscreens) | HtmlText    |
| [htmlLblErrorMsg (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#htmllblerrormsg)                    | HtmlText    |
| [icnReload (Home Screen)](screen-Home-Screen-Building-Access.md#icnreload)                                                                          | OnSelect    |
| [lblErrorMessage\_4 (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lblerrormessage_4)                                             | Text        |
| [lblErrorMessage\_4 (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lblerrormessage_4)                                             | Tooltip     |
| [lblErrorMessage\_KeyquestionsScreen (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#lblerrormessage_keyquestionsscreen)     | Text        |

#### varBackgroundImg

Variable used in:

| Control                                  | Property |
| ---------------------------------------- | -------- |
| [App ()](screen--Building-Access.md#app) | OnStart  |

#### varBuildingCardVisible

Variable used in:

| Control                                                                                                                                | Property  |
| -------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| [Approval Detail Screen (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#approval-detail-screen)             | OnHidden  |
| [Approval Detail Screen (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#approval-detail-screen)             | OnVisible |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)     | Visible   |
| [My Request Details Screen (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#my-request-details-screen) | OnVisible |

#### varErrorMessage

Variable used in:

| Control                                                                                                                                      | Property |
| -------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [btnSaveKeyQuestions (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#btnsavekeyquestions)     | OnSelect |
| [htmlLblErrorMsg (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#htmllblerrormsg)             | Visible  |
| [icnErrorCancel (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#icnerrorcancel)               | OnSelect |
| [icnErrorCancel (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#icnerrorcancel)               | Visible  |
| [icnErrorCancel\_ApproverScreen (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#icnerrorcancel_approverscreen)    | OnSelect |
| [imgErrorInfo (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#imgerrorinfo)                   | Visible  |
| [lblErrorBackRectangle (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#lblerrorbackrectangle) | Visible  |
| [lblErrorRectangle (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#lblerrorrectangle)         | Visible  |

#### varErrorMessageAppover

Variable used in:

| Control                                                                                                                                                 | Property |
| ------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [btnSave&NextApproverScreen (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#btnsave&nextapproverscreen)                      | OnSelect |
| [btnSave&NextDateScreen (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#btnsave&nextdatescreen)                                        | OnSelect |
| [icnErrorCancel\_ApproverScreen (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#icnerrorcancel_approverscreen)               | Visible  |
| [imgErrorInfo\_ApproverScreen (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#imgerrorinfo_approverscreen)                   | Visible  |
| [lblErrorBackRectangle\_ApproverScreen (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#lblerrorbackrectangle_approverscreen) | Visible  |
| [lblErrorMessage\_ApproverScreen (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#lblerrormessage_approverscreen)             | Visible  |
| [lblErrorRectangle\_ApproverScreen (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#lblerrorrectangle_approverscreen)         | Visible  |

#### varErrorMessageApproval

Variable used in:

| Control                                                                                                         | Property |
| --------------------------------------------------------------------------------------------------------------- | -------- |
| [btnApproveSelected (Approval Screen)](screen-Approval-Screen-Building-Access.md#btnapproveselected)            | OnSelect |
| [icnErrorCancel\_1 (Approval Screen)](screen-Approval-Screen-Building-Access.md#icnerrorcancel_1)               | OnSelect |
| [icnErrorCancel\_1 (Approval Screen)](screen-Approval-Screen-Building-Access.md#icnerrorcancel_1)               | Visible  |
| [icnErrorCancel\_2 (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#icnerrorcancel_2)     | OnSelect |
| [imgErrorInfo\_1 (Approval Screen)](screen-Approval-Screen-Building-Access.md#imgerrorinfo_1)                   | Visible  |
| [lblErrorBackRectangle\_1 (Approval Screen)](screen-Approval-Screen-Building-Access.md#lblerrorbackrectangle_1) | Visible  |
| [lblErrorMessage\_1 (Approval Screen)](screen-Approval-Screen-Building-Access.md#lblerrormessage_1)             | Visible  |
| [lblErrorRectangle\_1 (Approval Screen)](screen-Approval-Screen-Building-Access.md#lblerrorrectangle_1)         | Visible  |

#### varErrorMessageApprovalDetails

Variable used in:

| Control                                                                                                                       | Property |
| ----------------------------------------------------------------------------------------------------------------------------- | -------- |
| [btnRequestApprove (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btnrequestapprove)              | OnSelect |
| [icnErrorCancel\_3 (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#icnerrorcancel_3)               | OnSelect |
| [icnErrorCancel\_3 (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#icnerrorcancel_3)               | Visible  |
| [icnInformation (Approval Screen)](screen-Approval-Screen-Building-Access.md#icninformation)                                  | OnSelect |
| [imgErrorInfo\_3 (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#imgerrorinfo_3)                   | Visible  |
| [lblErrorBackRectangle\_3 (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#lblerrorbackrectangle_3) | Visible  |
| [lblErrorMessage\_3 (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#lblerrormessage_3)             | Visible  |
| [lblErrorRectangle\_3 (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#lblerrorrectangle_3)         | Visible  |

#### varErrorMessageDayLimit

Variable used in:

| Control                                                                                                             | Property |
| ------------------------------------------------------------------------------------------------------------------- | -------- |
| [datepkEndDate (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#datepkenddate)                      | OnChange |
| [datepkStartDate (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#datepkstartdate)                  | OnChange |
| [icnErrorCancel\_4 (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#icnerrorcancel_4)               | OnSelect |
| [icnErrorCancel\_4 (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#icnerrorcancel_4)               | Visible  |
| [imgErrorInfo\_4 (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#imgerrorinfo_4)                   | Visible  |
| [lblErrorBackRectangle\_4 (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lblerrorbackrectangle_4) | Visible  |
| [lblErrorMessage\_4 (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lblerrormessage_4)             | Visible  |
| [lblErrorRectangle\_4 (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lblerrorrectangle_4)         | Visible  |

#### varErrorMessageKeyquestionsScreen

Variable used in:

| Control                                                                                                                                                     | Property |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [btnSubmitKeyQuestions (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#btnsubmitkeyquestions)                                        | OnSelect |
| [htmlErrorMessage\_KeyquestionsScreens (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#htmlerrormessage_keyquestionsscreens)         | Visible  |
| [icnErrorCancel\_KeyquestionsScreen (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#icnerrorcancel_keyquestionsscreen)               | OnSelect |
| [icnErrorCancel\_KeyquestionsScreen (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#icnerrorcancel_keyquestionsscreen)               | Visible  |
| [imgErrorInfo\_KeyquestionsScreen (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#imgerrorinfo_keyquestionsscreen)                   | Visible  |
| [lblErrorBackRectangle\_KeyquestionsScreen (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#lblerrorbackrectangle_keyquestionsscreen) | Visible  |
| [lblErrorMessage\_KeyquestionsScreen (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#lblerrormessage_keyquestionsscreen)             | Visible  |
| [lblErrorRectangle\_KeyquestionsScreen (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#lblerrorrectangle_keyquestionsscreen)         | Visible  |

#### varErrorMessageRejection

Variable used in:

| Control                                                                                                                   | Property |
| ------------------------------------------------------------------------------------------------------------------------- | -------- |
| [btnRejectRequest (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#btnrejectrequest)                | OnSelect |
| [btnRejectSelected (Approval Screen)](screen-Approval-Screen-Building-Access.md#btnrejectselected)                        | OnSelect |
| [btnRequestReject (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btnrequestreject)            | OnSelect |
| [icnErrorCancel\_2 (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#icnerrorcancel_2)               | OnSelect |
| [icnErrorCancel\_2 (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#icnerrorcancel_2)               | Visible  |
| [imgErrorInfo\_2 (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#imgerrorinfo_2)                   | Visible  |
| [lblErrorBackRectangle\_2 (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#lblerrorbackrectangle_2) | Visible  |
| [lblErrorMessage\_2 (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#lblerrormessage_2)             | Visible  |
| [lblErrorRectangle\_2 (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#lblerrorrectangle_2)         | Visible  |

#### varKeyQuestionsPass

Variable used in:

| Control                                                                                                                                                            | Property  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------- |
| [Key Questions Screen (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#key-questions-screen)                                                 | OnVisible |
| [New Request Key Questions Screen (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#new-request-key-questions-screen) | OnVisible |

#### varKeyQuestionsRequiredPass

Variable used in:

| Control                                                                                                                                                            | Property  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------- |
| [Key Questions Screen (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#key-questions-screen)                                                 | OnVisible |
| [New Request Key Questions Screen (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#new-request-key-questions-screen) | OnVisible |

#### varLanguage

Variable used in:

| Control                                                                        | Property  |
| ------------------------------------------------------------------------------ | --------- |
| [App ()](screen--Building-Access.md#app)                                       | OnStart   |
| [Home Screen (Home Screen)](screen-Home-Screen-Building-Access.md#home-screen) | OnVisible |

#### varRequestAction

Variable used in:

| Control                                                                                                      | Property |
| ------------------------------------------------------------------------------------------------------------ | -------- |
| [btnWithdraw (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btnwithdraw)   | OnSelect |
| [btnYes (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btnyes)             | Text     |
| [lblAlertText (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblalerttext) | Text     |

#### VarRequestIstoday

Variable used in:

| Control                                                                                                                                | Property  |
| -------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| [My Request Details Screen (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#my-request-details-screen) | OnVisible |

#### varSelectedBuilding

Variable used in:

| Control                                                                                                                                        | Property     |
| ---------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| [btnCheckAvailability (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#btncheckavailability)                                   | OnSelect     |
| [btnCheckIn (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckin)                                       | OnSelect     |
| [btnCheckIn (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckin)                                       | Visible      |
| [btnCheckOut (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckout)                                     | OnSelect     |
| [btnCheckOut (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckout)                                     | Visible      |
| [btnSave&NextBuildingScreen (Building Screen)](screen-Building-Screen-Building-Access.md#btnsave&nextbuildingscreen)                           | OnSelect     |
| [btnSubmitKeyQuestions (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#btnsubmitkeyquestions)                           | OnSelect     |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)             | Building     |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)             | BuildingInfo |
| [Date Space Screen (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#date-space-screen)                                         | OnVisible    |
| [htmlOnsiteText (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#htmlonsitetext)                               | HtmlText     |
| [icnInformation (Approval Screen)](screen-Approval-Screen-Building-Access.md#icninformation)                                                   | OnSelect     |
| [imgInfo (Approval Screen)](screen-Approval-Screen-Building-Access.md#imginfo)                                                                 | OnSelect     |
| [lblCheckInTime (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblcheckintime)                               | Visible      |
| [lblCheckOutTime (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblcheckouttime)                             | Visible      |
| [lblMyRequestInstructionsValue (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestinstructionsvalue) | Text         |
| [lblTypeOfFacilityValue (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lbltypeoffacilityvalue)               | Text         |
| [My Request Details Screen (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#my-request-details-screen)         | OnVisible    |
| [My Request List Screen (My Request List Screen)](screen-My-Request-List-Screen-Building-Access.md#my-request-list-screen)                     | OnVisible    |
| [RequestQRCode (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#requestqrcode)                                 | Height       |
| [RequestQRCode (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#requestqrcode)                                 | Visible      |

#### varSelectedRequest

Variable used in:

| Control                                                                                                                                                          | Property           |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| [btnCheckIn (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckin)                                                         | DisplayMode        |
| [btnCheckIn (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckin)                                                         | OnSelect           |
| [btnCheckIn (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckin)                                                         | Visible            |
| [btnCheckOut (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckout)                                                       | DisplayMode        |
| [btnCheckOut (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckout)                                                       | OnSelect           |
| [btnCheckOut (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckout)                                                       | Visible            |
| [btnReject (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btnreject)                                                                 | OnSelect           |
| [btnReject (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btnreject)                                                                 | Text               |
| [btnRejectRequest (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#btnrejectrequest)                                                       | OnSelect           |
| [btnRequestApprove (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btnrequestapprove)                                                 | DisplayMode        |
| [btnRequestApprove (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btnrequestapprove)                                                 | OnSelect           |
| [btnSubmitKeyQuestions (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#btnsubmitkeyquestions)                                             | OnSelect           |
| [btnWithdraw (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btnwithdraw)                                                       | DisplayMode        |
| [btnYes (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btnyes)                                                                 | OnSelect           |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                               | ApprovedBy         |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                               | RequestDate        |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                               | Requestor          |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                               | RequestReason      |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                               | Space              |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                               | SubmittedDateValue |
| [ctrlRejectionReasonApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#ctrlrejectionreasonapprovaldetail)                 | Title              |
| [galleryTemplate5\_3 (Safety Precaution List Screen)](screen-Safety-Precaution-List-Screen-Building-Access.md#gallerytemplate5_3)                                | OnSelect           |
| [icnErrorCancel\_KeyquestionsScreen (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#icnerrorcancel_keyquestionsscreen)                    | OnSelect           |
| [icnErrorCancel\_KeyquestionsScreen\_1 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#icnerrorcancel_keyquestionsscreen_1)     | OnSelect           |
| [icnInformation (Approval Screen)](screen-Approval-Screen-Building-Access.md#icninformation)                                                                     | OnSelect           |
| [imgInfo (Approval Screen)](screen-Approval-Screen-Building-Access.md#imginfo)                                                                                   | OnSelect           |
| [lblCheckInTime (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblcheckintime)                                                 | Text               |
| [lblCheckInTime (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblcheckintime)                                                 | Visible            |
| [lblCheckOutTime (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblcheckouttime)                                               | Text               |
| [lblCheckOutTime (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblcheckouttime)                                               | Visible            |
| [lblMyRequestApproverValue (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestapprovervalue)                           | Text               |
| [lblMyRequestBusinessJustificationValue (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestbusinessjustificationvalue) | Text               |
| [lblMyRequestCheckInStatus (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestcheckinstatus)                           | Text               |
| [lblMyRequestCheckInStatusValue (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestcheckinstatusvalue)                 | Text               |
| [lblMyRequestDateValue (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestdatevalue)                                   | Text               |
| [lblMyRequestStatusValue (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequeststatusvalue)                               | Text               |
| [lblReservedTimeValue (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblreservedtimevalue)                                     | Text               |
| [My Request Details Screen (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#my-request-details-screen)                           | OnVisible          |
| [My Request List Screen (My Request List Screen)](screen-My-Request-List-Screen-Building-Access.md#my-request-list-screen)                                       | OnVisible          |
| [RequestQRCode (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#requestqrcode)                                                   | Code               |
| [RequestQRCode (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#requestqrcode)                                                   | Height             |
| [RequestQRCode (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#requestqrcode)                                                   | Visible            |

#### varShowApproved

Variable used in:

| Control                                                                                              | Property    |
| ---------------------------------------------------------------------------------------------------- | ----------- |
| [btnApproveSelected (Approval Screen)](screen-Approval-Screen-Building-Access.md#btnapproveselected) | DisplayMode |
| [btnRejectSelected (Approval Screen)](screen-Approval-Screen-Building-Access.md#btnrejectselected)   | DisplayMode |
| [Home Screen (Home Screen)](screen-Home-Screen-Building-Access.md#home-screen)                       | OnVisible   |
| [icnFilter (Approval Screen)](screen-Approval-Screen-Building-Access.md#icnfilter)                   | OnSelect    |

#### varShowLoading

Variable used in:

| Control                                                                                          | Property |
| ------------------------------------------------------------------------------------------------ | -------- |
| [btnYes (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btnyes) | OnSelect |

#### varShowRejectPopup

Variable used in:

| Control                                                                                                                                          | Property |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | -------- |
| [AlertBackDrop (Approval Screen)](screen-Approval-Screen-Building-Access.md#alertbackdrop)                                                       | Visible  |
| [btnCancel (Approval Screen)](screen-Approval-Screen-Building-Access.md#btncancel)                                                               | OnSelect |
| [btnCancel (Approval Screen)](screen-Approval-Screen-Building-Access.md#btncancel)                                                               | Visible  |
| [btnCancelReject (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btncancelreject)                                     | OnSelect |
| [btnCancelReject (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btncancelreject)                                     | Visible  |
| [btnReject (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btnreject)                                                 | OnSelect |
| [btnReject (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btnreject)                                                 | Visible  |
| [btnRejectApproval (Approval Screen)](screen-Approval-Screen-Building-Access.md#btnrejectapproval)                                               | OnSelect |
| [btnRejectApproval (Approval Screen)](screen-Approval-Screen-Building-Access.md#btnrejectapproval)                                               | Visible  |
| [ctrlRejectionReason (Approval Screen)](screen-Approval-Screen-Building-Access.md#ctrlrejectionreason)                                           | Visible  |
| [ctrlRejectionReasonApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#ctrlrejectionreasonapprovaldetail) | Visible  |
| [rctAlertBackDropApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#rctalertbackdropapprovaldetail)       | Visible  |

#### varString

Variable used in:

| Control                                                                                                                                                                      | Property                    |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------- |
| [App ()](screen--Building-Access.md#app)                                                                                                                                     | OnStart                     |
| [btnCancel (Approval Screen)](screen-Approval-Screen-Building-Access.md#btncancel)                                                                                           | Text                        |
| [btnCancelReject (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btncancelreject)                                                                 | Text                        |
| [btnCancelRequest (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#btncancelrequest)                                                                   | Text                        |
| [btnNo (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btnno)                                                                               | Text                        |
| [btnReject (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btnreject)                                                                             | OnSelect                    |
| [btnReject (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btnreject)                                                                             | Text                        |
| [btnRejectApproval (Approval Screen)](screen-Approval-Screen-Building-Access.md#btnrejectapproval)                                                                           | OnSelect                    |
| [btnRejectApproval (Approval Screen)](screen-Approval-Screen-Building-Access.md#btnrejectapproval)                                                                           | Text                        |
| [btnRequestApprove (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btnrequestapprove)                                                             | Text                        |
| [btnSave&NextApproverScreen (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#btnsave&nextapproverscreen)                                           | Text                        |
| [btnSubmitKeyQuestions (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#btnsubmitkeyquestions)                                                         | Text                        |
| [btnYes (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btnyes)                                                                             | Text                        |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                                           | Addresslbl                  |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                                           | BuildingInfo                |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                                           | BuildingTypelbl             |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                                           | OnsiteAccessInstructionslbl |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                                           | RequestApprovedbylbl        |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                                           | RequestDatelbl              |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                                           | RequestReasonLbl            |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                                           | ReuquestedBylbl             |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                                           | SpaceReservedLbl            |
| [ctrlRejectionReason (Approval Screen)](screen-Approval-Screen-Building-Access.md#ctrlrejectionreason)                                                                       | Title                       |
| [ctrlRejectionReasonApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#ctrlrejectionreasonapprovaldetail)                             | Title                       |
| [HeaderControlApproval (Approval Screen)](screen-Approval-Screen-Building-Access.md#headercontrolapproval)                                                                   | Text                        |
| [HeaderControlApprovalRequestDetails (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#headercontrolapprovalrequestdetails)                         | Text                        |
| [HeaderControlKeyEligibilityQuestions (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#headercontrolkeyeligibilityquestions)                           | Text                        |
| [HeaderControlMyRequestList (My Request List Screen)](screen-My-Request-List-Screen-Building-Access.md#headercontrolmyrequestlist)                                           | Text                        |
| [HeaderControlRejectionReason (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#headercontrolrejectionreason)                                           | Text                        |
| [HeaderControlRequestDetails (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#headercontrolrequestdetails)                                   | Text                        |
| [HeaderControlSafetyPrecautions (Safety Precaution List Screen)](screen-Safety-Precaution-List-Screen-Building-Access.md#headercontrolsafetyprecautions)                     | Text                        |
| [HeaderControlSafetyPrecautionsDetails (Safety Precaution Details Screen)](screen-Safety-Precaution-Details-Screen-Building-Access.md#headercontrolsafetyprecautionsdetails) | Text                        |
| [Home Screen (Home Screen)](screen-Home-Screen-Building-Access.md#home-screen)                                                                                               | OnVisible                   |
| [htmlEligibilityText (Building Screen)](screen-Building-Screen-Building-Access.md#htmleligibilitytext)                                                                       | HtmlText                    |
| [htmlErrorMessage\_KeyquestionsScreens (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#htmlerrormessage_keyquestionsscreens)                          | Color                       |
| [htmlErrorMessage\_KeyquestionsScreens (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#htmlerrormessage_keyquestionsscreens)                          | Height                      |
| [icnReload (Home Screen)](screen-Home-Screen-Building-Access.md#icnreload)                                                                                                   | OnSelect                    |
| [lblAlertText (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblalerttext)                                                                 | Text                        |
| [lblAlertTitle (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblalerttitle)                                                               | Text                        |
| [lblBusinessReason (Building Screen)](screen-Building-Screen-Building-Access.md#lblbusinessreason)                                                                           | Text                        |
| [lblEligibility (Building Screen)](screen-Building-Screen-Building-Access.md#lbleligibility)                                                                                 | Text                        |
| [lblErrorMessage\_1 (Approval Screen)](screen-Approval-Screen-Building-Access.md#lblerrormessage_1)                                                                          | Text                        |
| [lblErrorMessage\_2 (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#lblerrormessage_2)                                                                | Text                        |
| [lblErrorMessage\_3 (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#lblerrormessage_3)                                                            | Text                        |
| [lblErrorMessage\_5 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblerrormessage_5)                                                      | Text                        |
| [lblErrorMessage\_KeyquestionsScreen (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#lblerrormessage_keyquestionsscreen)                              | Height                      |
| [lblErrorMessage\_KeyquestionsScreen\_1 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblerrormessage_keyquestionsscreen_1)               | Text                        |
| [lblKeyQuestionsHeader (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#lblkeyquestionsheader)                                 | Text                        |
| [lblLastUpdated (Safety Precaution List Screen)](screen-Safety-Precaution-List-Screen-Building-Access.md#lbllastupdated)                                                     | Text                        |
| [lblLastUpdatedSafetyPrecaution (Safety Precaution Details Screen)](screen-Safety-Precaution-Details-Screen-Building-Access.md#lbllastupdatedsafetyprecaution)               | Text                        |
| [lblMyRequestApprover (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestapprover)                                                 | Text                        |
| [lblMyRequestBusinessJustification (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestbusinessjustification)                       | Text                        |
| [lblMyRequestCheckInStatus (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestcheckinstatus)                                       | Text                        |
| [lblMyRequestCheckInStatusValue (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestcheckinstatusvalue)                             | Text                        |
| [lblMyRequestDate (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestdate)                                                         | Text                        |
| [lblMyRequestInstructions (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestinstructions)                                         | Text                        |
| [lblMyRequestStatus (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequeststatus)                                                     | Text                        |
| [lblRequestStatus (My Request List Screen)](screen-My-Request-List-Screen-Building-Access.md#lblrequeststatus)                                                               | Text                        |
| [lblRequestSummary (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#lblrequestsummary)                                                             | Text                        |
| [lblSelectAll (Approval Screen)](screen-Approval-Screen-Building-Access.md#lblselectall)                                                                                     | Text                        |
| [lblSelectBuilding (Building Screen)](screen-Building-Screen-Building-Access.md#lblselectbuilding)                                                                           | Text                        |
| [lblSelectDate\/SpaceHeader (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lblselectdate/spaceheader)                                                      | Text                        |
| [lblSelectSpace (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lblselectspace)                                                                             | Text                        |
| [lblTodaysReservation (Home Screen)](screen-Home-Screen-Building-Access.md#lbltodaysreservation)                                                                             | Text                        |
| [lblUserTitle (Home Screen)](screen-Home-Screen-Building-Access.md#lblusertitle)                                                                                             | Text                        |
| [RejectionReasonComponent (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#rejectionreasoncomponent)                                                   | Title                       |
| [txtApprovalsSearch (Approval Screen)](screen-Approval-Screen-Building-Access.md#txtapprovalssearch)                                                                         | HintText                    |
| [txtEligibilityCriteria (Building Screen)](screen-Building-Screen-Building-Access.md#txteligibilitycriteria)                                                                 | HintText                    |
| [txtSearchBox (Safety Precaution List Screen)](screen-Safety-Precaution-List-Screen-Building-Access.md#txtsearchbox)                                                         | HintText                    |
| [txtSearchRequestBox (My Request List Screen)](screen-My-Request-List-Screen-Building-Access.md#txtsearchrequestbox)                                                         | HintText                    |

#### varStringExt

Variable used in:

| Control                                                                        | Property  |
| ------------------------------------------------------------------------------ | --------- |
| [App ()](screen--Building-Access.md#app)                                       | OnStart   |
| [Home Screen (Home Screen)](screen-Home-Screen-Building-Access.md#home-screen) | OnVisible |

#### varStringNew

Variable used in:

| Control                                                                                                                                                        | Property             |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| [App ()](screen--Building-Access.md#app)                                                                                                                       | OnStart              |
| [btnApproveSelected (Approval Screen)](screen-Approval-Screen-Building-Access.md#btnapproveselected)                                                           | Text                 |
| [btnBackApproverScreen (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#btnbackapproverscreen)                                       | Text                 |
| [btnBackBuildingScreen (Building Screen)](screen-Building-Screen-Building-Access.md#btnbackbuildingscreen)                                                     | Text                 |
| [btnBackDateScreen (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#btnbackdatescreen)                                                         | Text                 |
| [btnCheckAvailability (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#btncheckavailability)                                                   | OnSelect             |
| [btnCheckAvailability (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#btncheckavailability)                                                   | Text                 |
| [btnCheckIn (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckin)                                                       | Text                 |
| [btnCheckOut (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckout)                                                     | Text                 |
| [btnRejectRequest (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#btnrejectrequest)                                                     | OnSelect             |
| [btnRejectRequest (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#btnrejectrequest)                                                     | Text                 |
| [btnRejectSelected (Approval Screen)](screen-Approval-Screen-Building-Access.md#btnrejectselected)                                                             | Text                 |
| [btnRequestReject (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#btnrequestreject)                                                 | Text                 |
| [btnSave&NextBuildingScreen (Building Screen)](screen-Building-Screen-Building-Access.md#btnsave&nextbuildingscreen)                                           | Text                 |
| [btnSave&NextDateScreen (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#btnsave&nextdatescreen)                                               | Text                 |
| [btnSaveKeyQuestions (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#btnsavekeyquestions)                       | Text                 |
| [btnSaveKeyQuestions\_1 (My Request List Screen)](screen-My-Request-List-Screen-Building-Access.md#btnsavekeyquestions_1)                                      | Text                 |
| [btnWithdraw (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btnwithdraw)                                                     | Text                 |
| [btnYes (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btnyes)                                                               | OnSelect             |
| [BuildingCardApprovalDetail (Approval Detail Screen)](screen-Approval-Detail-Screen-Building-Access.md#buildingcardapprovaldetail)                             | Spacelbl             |
| [chkSetDefaultApprover (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#chksetdefaultapprover)                                       | Text                 |
| [cmbSelectBuilding (Building Screen)](screen-Building-Screen-Building-Access.md#cmbselectbuilding)                                                             | InputTextPlaceholder |
| [cmbSelectSlot (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#cmbselectslot)                                                                 | InputTextPlaceholder |
| [cmbSelectSlot (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#cmbselectslot)                                                                 | NoSelectionText      |
| [cmbSelectSpace (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#cmbselectspace)                                                               | InputTextPlaceholder |
| [cmbSelectSpace (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#cmbselectspace)                                                               | NoSelectionText      |
| [glryAvailableDate&Space (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#glryavailabledate&space)                                             | Items                |
| [glryRequiredDate&Space (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#glryrequireddate&space)                                     | Items                |
| [HeaderControlKeyQuestions (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#headercontrolkeyquestions)           | Text                 |
| [HeaderControlSelectApprover (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#headercontrolselectapprover)                           | Text                 |
| [HeaderControlSelectBuilding (Building Screen)](screen-Building-Screen-Building-Access.md#headercontrolselectbuilding)                                         | Text                 |
| [HeaderControlSelectDateAndSpace (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#headercontrolselectdateandspace)                             | Text                 |
| [Home Screen (Home Screen)](screen-Home-Screen-Building-Access.md#home-screen)                                                                                 | OnVisible            |
| [htmlErrorMessage\_KeyquestionsScreens (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#htmlerrormessage_keyquestionsscreens)            | Color                |
| [htmlErrorMessage\_KeyquestionsScreens (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#htmlerrormessage_keyquestionsscreens)            | Height               |
| [htmlErrorMessage\_KeyquestionsScreens (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#htmlerrormessage_keyquestionsscreens)            | HtmlText             |
| [htmlLblErrorMsg (New Request Key Questions Screen)](screen-New-Request-Key-Questions-Screen-Building-Access.md#htmllblerrormsg)                               | HtmlText             |
| [icnNextArrow2 (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#icnnextarrow2)                                                                 | OnSelect             |
| [icnNextArrow3 (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#icnnextarrow3)                                                       | OnSelect             |
| [lblBuildingName (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#lblbuildingname)                                                   | Text                 |
| [lblDateAndSpaceError (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lbldateandspaceerror)                                                   | Text                 |
| [lblEndDate (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lblenddate)                                                                       | Text                 |
| [lblErrorMessage\_4 (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lblerrormessage_4)                                                        | Text                 |
| [lblErrorMessage\_ApproverScreen (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#lblerrormessage_approverscreen)                    | Text                 |
| [lblErrorMessage\_KeyquestionsScreen (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#lblerrormessage_keyquestionsscreen)                | Height               |
| [lblErrorMessage\_KeyquestionsScreen (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#lblerrormessage_keyquestionsscreen)                | Text                 |
| [lblLastUpdated (Safety Precaution List Screen)](screen-Safety-Precaution-List-Screen-Building-Access.md#lbllastupdated)                                       | Text                 |
| [lblLastUpdatedSafetyPrecaution (Safety Precaution Details Screen)](screen-Safety-Precaution-Details-Screen-Building-Access.md#lbllastupdatedsafetyprecaution) | Text                 |
| [lblMyRequestCheckInStatus (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestcheckinstatus)                         | Text                 |
| [lblMyRequestCheckInStatusValue (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequestcheckinstatusvalue)               | Text                 |
| [lblMyRequestStatusValue (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblmyrequeststatusvalue)                             | Text                 |
| [lblNoApprover (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#lblnoapprover)                                                       | Text                 |
| [lblRequestStatus (My Request List Screen)](screen-My-Request-List-Screen-Building-Access.md#lblrequeststatus)                                                 | Text                 |
| [lblReservedSpaces (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lblreservedspaces)                                                         | Text                 |
| [lblReservedTime (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblreservedtime)                                             | Text                 |
| [lblReservedTimeValue (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblreservedtimevalue)                                   | Text                 |
| [lblSeats (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblseats)                                                           | Text                 |
| [lblSelectBuildingHeader (Building Screen)](screen-Building-Screen-Building-Access.md#lblselectbuildingheader)                                                 | Text                 |
| [lblSelectedDateAndSpace (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lblselecteddateandspace)                                             | Text                 |
| [lblSelectSlot (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lblselectslot)                                                                 | Text                 |
| [lblStartDate (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lblstartdate)                                                                   | Text                 |
| [lblTimeSlot (Home Screen)](screen-Home-Screen-Building-Access.md#lbltimeslot)                                                                                 | Text                 |
| [lblTimeSlotError (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lbltimesloterror)                                                           | Text                 |
| [lblToggleButton (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#lbltogglebutton)                                                             | Text                 |
| [lblTypeOfFacility (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lbltypeoffacility)                                         | Text                 |
| [lblTypeOfFacilityValue (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lbltypeoffacilityvalue)                               | Text                 |
| [lblUserDescription (Home Screen)](screen-Home-Screen-Building-Access.md#lbluserdescription)                                                                   | Text                 |
| [RejectionReasonComponent (Reject Reason Screen)](screen-Reject-Reason-Screen-Building-Access.md#rejectionreasoncomponent)                                     | HintText             |
| [selectAlternateApproverCombobox (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#selectalternateapprovercombobox)                   | InputTextPlaceholder |
| [selectAlternateApproverCombobox (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#selectalternateapprovercombobox)                   | NoSelectionText      |
| [selectApproverLbl (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#selectapproverlbl)                                               | Text                 |
| [selectApproverLbl\_1 (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#selectapproverlbl_1)                                          | Text                 |
| [selectApproverLbl\_3 (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#selectapproverlbl_3)                                          | Text                 |
| [txtBusinessReason (Building Screen)](screen-Building-Screen-Building-Access.md#txtbusinessreason)                                                             | HintText             |

#### varSuccessCheckInMessage

Variable used in:

| Control                                                                                                                                                                    | Property |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [btnCheckIn (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckin)                                                                   | OnSelect |
| [icnErrorCancel\_KeyquestionsScreen\_1 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#icnerrorcancel_keyquestionsscreen_1)               | OnSelect |
| [icnErrorCancel\_KeyquestionsScreen\_1 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#icnerrorcancel_keyquestionsscreen_1)               | Visible  |
| [imgErrorInfo\_KeyquestionsScreen\_1 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#imgerrorinfo_keyquestionsscreen_1)                   | Visible  |
| [lblErrorBackRectangle\_KeyquestionsScreen\_1 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblerrorbackrectangle_keyquestionsscreen_1) | Visible  |
| [lblErrorMessage\_KeyquestionsScreen\_1 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblerrormessage_keyquestionsscreen_1)             | Visible  |
| [lblErrorRectangle\_KeyquestionsScreen\_1 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblerrorrectangle_keyquestionsscreen_1)         | Visible  |

#### varSuccessCheckoutMessage

Variable used in:

| Control                                                                                                                             | Property |
| ----------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [btnCheckOut (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckout)                          | OnSelect |
| [icnErrorCancel\_5 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#icnerrorcancel_5)               | OnSelect |
| [icnErrorCancel\_5 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#icnerrorcancel_5)               | Visible  |
| [imgErrorInfo\_5 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#imgerrorinfo_5)                   | Visible  |
| [lblErrorBackRectangle\_5 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblerrorbackrectangle_5) | Visible  |
| [lblErrorMessage\_5 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblerrormessage_5)             | Visible  |
| [lblErrorRectangle\_5 (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#lblerrorrectangle_5)         | Visible  |

#### varTodayFormated

Variable used in:

| Control                                                                                                                                | Property  |
| -------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| [App ()](screen--Building-Access.md#app)                                                                                               | OnStart   |
| [btnCheckIn (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckin)                               | OnSelect  |
| [btnCheckOut (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#btncheckout)                             | OnSelect  |
| [btnSubmitKeyQuestions (Key Questions Screen)](screen-Key-Questions-Screen-Building-Access.md#btnsubmitkeyquestions)                   | OnSelect  |
| [Home Screen (Home Screen)](screen-Home-Screen-Building-Access.md#home-screen)                                                         | OnVisible |
| [icnFilter (Approval Screen)](screen-Approval-Screen-Building-Access.md#icnfilter)                                                     | OnSelect  |
| [icnReload (Home Screen)](screen-Home-Screen-Building-Access.md#icnreload)                                                             | OnSelect  |
| [My Request Details Screen (My Request Details Screen)](screen-My-Request-Details-Screen-Building-Access.md#my-request-details-screen) | OnVisible |

#### varUser

Variable used in:

| Control                                                                                                                            | Property    |
| ---------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| [App ()](screen--Building-Access.md#app)                                                                                           | OnStart     |
| [Approval Screen (Approval Screen)](screen-Approval-Screen-Building-Access.md#approval-screen)                                     | OnVisible   |
| [btnCheckAvailability (Date Space Screen)](screen-Date-Space-Screen-Building-Access.md#btncheckavailability)                       | OnSelect    |
| [btnSave&NextApproverScreen (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#btnsave&nextapproverscreen) | DisplayMode |
| [Home Screen (Home Screen)](screen-Home-Screen-Building-Access.md#home-screen)                                                     | OnVisible   |
| [icnFilter (Approval Screen)](screen-Approval-Screen-Building-Access.md#icnfilter)                                                 | OnSelect    |
| [icnReload (Home Screen)](screen-Home-Screen-Building-Access.md#icnreload)                                                         | OnSelect    |
| [My Request List Screen (My Request List Screen)](screen-My-Request-List-Screen-Building-Access.md#my-request-list-screen)         | OnVisible   |
| [selectApproverLbl\_2 (Select Approver Screen)](screen-Select-Approver-Screen-Building-Access.md#selectapproverlbl_2)              | Text        |

### Context Variables

### Collections

#### AllSlot

#### AllSlots

Variable used in:

| Control                                  | Property |
| ---------------------------------------- | -------- |
| btnCheckAvailability (Date Space Screen) | OnSelect |

#### colA

Variable used in:

| Control                                  | Property |
| ---------------------------------------- | -------- |
| btnCheckAvailability (Date Space Screen) | OnSelect |

#### colAddRequestDates

Variable used in:

| Control                                             | Property  |
| --------------------------------------------------- | --------- |
| btnSave&NextApproverScreen (Select Approver Screen) | OnSelect  |
| Home Screen (Home Screen)                           | OnVisible |

#### colAlertComponent

Variable used in:

| Control                                               | Property  |
| ----------------------------------------------------- | --------- |
| btnNo (My Request Details Screen)                     | OnSelect  |
| btnNo (My Request Details Screen)                     | Visible   |
| btnWithdraw (My Request Details Screen)               | OnSelect  |
| btnYes (My Request Details Screen)                    | OnSelect  |
| btnYes (My Request Details Screen)                    | Visible   |
| lblAlertText (My Request Details Screen)              | Visible   |
| lblAlertTitle (My Request Details Screen)             | OnSelect  |
| lblAlertTitle (My Request Details Screen)             | Visible   |
| My Request Details Screen (My Request Details Screen) | OnVisible |
| rectBackDrop (My Request Details Screen)              | Visible   |
| rectOptionsBox (My Request Details Screen)            | Visible   |
| rectPopupBox (My Request Details Screen)              | Visible   |

#### colB

Variable used in:

| Control                                  | Property |
| ---------------------------------------- | -------- |
| btnCheckAvailability (Date Space Screen) | OnSelect |

#### colBuildingRequests

Variable used in:

| Control                                      | Property |
| -------------------------------------------- | -------- |
| btnCheckIn (My Request Details Screen)       | OnSelect |
| btnCheckOut (My Request Details Screen)      | OnSelect |
| btnSubmitKeyQuestions (Key Questions Screen) | OnSelect |

#### colBuildings

Variable used in:

| Control                             | Property    |
| ----------------------------------- | ----------- |
| Building Screen (Building Screen)   | OnVisible   |
| cmbSelectBuilding (Building Screen) | Items       |
| cmbSelectBuilding (Building Screen) | SearchItems |

#### colC

Variable used in:

| Control                                  | Property |
| ---------------------------------------- | -------- |
| btnCheckAvailability (Date Space Screen) | OnSelect |

#### colD

#### colDateRanges

Variable used in:

| Control                                             | Property  |
| --------------------------------------------------- | --------- |
| btnBackDateScreen (Date Space Screen)               | OnSelect  |
| btnCheckAvailability (Date Space Screen)            | OnSelect  |
| btnSave&NextApproverScreen (Select Approver Screen) | OnSelect  |
| Building Screen (Building Screen)                   | OnVisible |
| Home Screen (Home Screen)                           | OnVisible |

#### colDatesFullyOccupied

Variable used in:

| Control                                  | Property |
| ---------------------------------------- | -------- |
| btnCheckAvailability (Date Space Screen) | OnSelect |

#### colDatesNotOccupied

Variable used in:

| Control                                             | Property  |
| --------------------------------------------------- | --------- |
| btnBackDateScreen (Date Space Screen)               | OnSelect  |
| btnCheckAvailability (Date Space Screen)            | OnSelect  |
| btnSave&NextApproverScreen (Select Approver Screen) | OnSelect  |
| Building Screen (Building Screen)                   | OnVisible |
| Home Screen (Home Screen)                           | OnVisible |

#### colDatesOccupied

Variable used in:

| Control                                             | Property  |
| --------------------------------------------------- | --------- |
| btnBackDateScreen (Date Space Screen)               | OnSelect  |
| btnCheckAvailability (Date Space Screen)            | OnSelect  |
| btnSave&NextApproverScreen (Select Approver Screen) | OnSelect  |
| Building Screen (Building Screen)                   | OnVisible |
| glryRequiredDate&Space (Select Approver Screen)     | Items     |
| glryReservedDate&Space (Date Space Screen)          | Items     |
| Home Screen (Home Screen)                           | OnVisible |
| icnNextArrow (Date Space Screen)                    | OnSelect  |

#### colDatesOccupiedNew

Variable used in:

| Control                                  | Property |
| ---------------------------------------- | -------- |
| btnCheckAvailability (Date Space Screen) | OnSelect |

#### colE

Variable used in:

| Control                                  | Property |
| ---------------------------------------- | -------- |
| btnCheckAvailability (Date Space Screen) | OnSelect |

#### colFloors

Variable used in:

| Control                               | Property    |
| ------------------------------------- | ----------- |
| cmbSelectSpace (Date Space Screen)    | Items       |
| cmbSelectSpace (Date Space Screen)    | SearchItems |
| Date Space Screen (Date Space Screen) | OnVisible   |

#### colFlowResponse

Variable used in:

| Control                                             | Property |
| --------------------------------------------------- | -------- |
| btnSave&NextApproverScreen (Select Approver Screen) | OnSelect |

#### colKeyQuestions

Variable used in:

| Control                                                             | Property  |
| ------------------------------------------------------------------- | --------- |
| Key Questions Screen (Key Questions Screen)                         | OnVisible |
| New Request Key Questions Screen (New Request Key Questions Screen) | OnVisible |

#### colLocalQuestionAnswers

Variable used in:

| Control                                                             | Property  |
| ------------------------------------------------------------------- | --------- |
| Key Questions Screen (Key Questions Screen)                         | OnVisible |
| New Request Key Questions Screen (New Request Key Questions Screen) | OnVisible |

#### colMyApprovals

Variable used in:

| Control                                     | Property  |
| ------------------------------------------- | --------- |
| App ()                                      | OnStart   |
| Approval Screen (Approval Screen)           | OnVisible |
| btnApproveSelected (Approval Screen)        | OnSelect  |
| btnReject (Approval Detail Screen)          | OnSelect  |
| btnRejectApproval (Approval Screen)         | OnSelect  |
| btnRejectRequest (Reject Reason Screen)     | OnSelect  |
| btnRequestApprove (Approval Detail Screen)  | OnSelect  |
| chkSelectAll (Approval Screen)              | OnCheck   |
| glryApprovals (Approval Screen)             | Items     |
| Home Screen (Home Screen)                   | OnVisible |
| icnFilter (Approval Screen)                 | OnSelect  |
| icnReload (Home Screen)                     | OnSelect  |
| Reject Reason Screen (Reject Reason Screen) | OnVisible |

#### colNav

Variable used in:

| Control                     | Property  |
| --------------------------- | --------- |
| App ()                      | OnStart   |
| Home Screen (Home Screen)   | OnVisible |
| HomePageMenus (Home Screen) | Items     |
| icnReload (Home Screen)     | OnSelect  |

#### colNewDatesNotOccupied

Variable used in:

| Control                                             | Property  |
| --------------------------------------------------- | --------- |
| btnBackDateScreen (Date Space Screen)               | OnSelect  |
| btnCheckAvailability (Date Space Screen)            | OnSelect  |
| btnSave&NextApproverScreen (Select Approver Screen) | OnSelect  |
| Building Screen (Building Screen)                   | OnVisible |
| glryAvailableDate&Space (Date Space Screen)         | Items     |
| glryRequiredDate&Space (Select Approver Screen)     | Items     |
| Home Screen (Home Screen)                           | OnVisible |
| icnNextArrow2 (Date Space Screen)                   | OnSelect  |
| icnNextArrow3 (Select Approver Screen)              | OnSelect  |

#### colQuestionAnswersResponse

Variable used in:

| Control                                                             | Property    |
| ------------------------------------------------------------------- | ----------- |
| btnSaveKeyQuestions (New Request Key Questions Screen)              | DisplayMode |
| btnSaveKeyQuestions (New Request Key Questions Screen)              | OnSelect    |
| btnSubmitKeyQuestions (Key Questions Screen)                        | OnSelect    |
| htmlErrorMessage\_KeyquestionsScreens (Key Questions Screen)        | HtmlText    |
| htmlLblErrorMsg (New Request Key Questions Screen)                  | HtmlText    |
| imgErrorInfo\_KeyquestionsScreen (Key Questions Screen)             | Image       |
| Key Questions Screen (Key Questions Screen)                         | OnVisible   |
| lblErrorMessage\_KeyquestionsScreen (Key Questions Screen)          | Text        |
| New Request Key Questions Screen (New Request Key Questions Screen) | OnVisible   |

#### colRecordsByDateFilter

Variable used in:

| Control                                  | Property |
| ---------------------------------------- | -------- |
| btnCheckAvailability (Date Space Screen) | OnSelect |

#### colRequiredSlots

Variable used in:

| Control                                             | Property  |
| --------------------------------------------------- | --------- |
| btnCheckAvailability (Date Space Screen)            | OnSelect  |
| btnSave&NextApproverScreen (Select Approver Screen) | OnSelect  |
| Building Screen (Building Screen)                   | OnVisible |

#### colReservedSpaces

Variable used in:

| Control                                             | Property  |
| --------------------------------------------------- | --------- |
| btnBackDateScreen (Date Space Screen)               | OnSelect  |
| btnCheckAvailability (Date Space Screen)            | OnSelect  |
| btnSave&NextApproverScreen (Select Approver Screen) | OnSelect  |
| Building Screen (Building Screen)                   | OnVisible |
| glryRequiredDate&Space (Select Approver Screen)     | Items     |
| glryReservedSpace (Date Space Screen)               | Items     |
| Home Screen (Home Screen)                           | OnVisible |

#### colReservedSpacesNew

Variable used in:

| Control                                  | Property |
| ---------------------------------------- | -------- |
| btnCheckAvailability (Date Space Screen) | OnSelect |

#### colSafetyPrecautions

Variable used in:

| Control                                                       | Property  |
| ------------------------------------------------------------- | --------- |
| glrySafetyPrecautions. (Safety Precaution List Screen)        | Items     |
| Safety Precaution List Screen (Safety Precaution List Screen) | OnVisible |

#### colSelectedApprovals

Variable used in:

| Control                                 | Property    |
| --------------------------------------- | ----------- |
| btnApproveSelected (Approval Screen)    | DisplayMode |
| btnApproveSelected (Approval Screen)    | OnSelect    |
| btnRejectApproval (Approval Screen)     | OnSelect    |
| btnRejectRequest (Reject Reason Screen) | OnSelect    |
| btnRejectSelected (Approval Screen)     | DisplayMode |
| chkSelectAll (Approval Screen)          | OnCheck     |
| chkSelectAll (Approval Screen)          | OnUncheck   |
| chkSelectRequest (Approval Screen)      | Default     |
| chkSelectRequest (Approval Screen)      | OnCheck     |
| chkSelectRequest (Approval Screen)      | OnUncheck   |

#### colSelectedBuilding

Variable used in:

| Control                                      | Property |
| -------------------------------------------- | -------- |
| btnSave&NextBuildingScreen (Building Screen) | OnSelect |
| cmbSelectBuilding (Building Screen)          | OnSelect |

#### colSelectedRequest

Variable used in:

| Control                                               | Property  |
| ----------------------------------------------------- | --------- |
| App ()                                                | OnStart   |
| galleryTemplate6\_1 (My Request List Screen)          | OnSelect  |
| Home Screen (Home Screen)                             | OnVisible |
| icnReload (Home Screen)                               | OnSelect  |
| imgArrow (Home Screen)                                | OnSelect  |
| My Request Details Screen (My Request Details Screen) | OnVisible |

#### colSelectedRequests

Variable used in:

| Control                                             | Property |
| --------------------------------------------------- | -------- |
| galleryTemplate5\_3 (Safety Precaution List Screen) | OnSelect |

#### colSelectedSafetyPrecation

Variable used in:

| Control                                                        | Property |
| -------------------------------------------------------------- | -------- |
| glrySafetyPrecautionDetails (Safety Precaution Details Screen) | Items    |
| imgRightArrow (Safety Precaution List Screen)                  | OnSelect |
| shpRectangleBackground\_1 (Safety Precaution List Screen)      | OnSelect |

#### colTotalSeatsPerFloor

Variable used in:

| Control                                  | Property |
| ---------------------------------------- | -------- |
| btnCheckAvailability (Date Space Screen) | OnSelect |

#### colTranslation

Variable used in:

| Control                                                       | Property  |
| ------------------------------------------------------------- | --------- |
| Safety Precaution List Screen (Safety Precaution List Screen) | OnVisible |

#### colUserRequests

Variable used in:

| Control                                         | Property  |
| ----------------------------------------------- | --------- |
| glryMyRequest (My Request List Screen)          | Items     |
| Home Screen (Home Screen)                       | OnVisible |
| My Request List Screen (My Request List Screen) | OnVisible |

#### colUserRequestsToday

Variable used in:

| Control                             | Property  |
| ----------------------------------- | --------- |
| glryReservation (Home Screen)       | Height    |
| glryReservation (Home Screen)       | Items     |
| glryReservation (Home Screen)       | Visible   |
| Home Screen (Home Screen)           | OnVisible |
| lblTodaysReservation (Home Screen)  | Visible   |
| lblUserDescription (Home Screen)    | Y         |
| shpSeparatorRectangle (Home Screen) | Visible   |

#### PossiblesSlots

Variable used in:

| Control                                             | Property  |
| --------------------------------------------------- | --------- |
| btnBackDateScreen (Date Space Screen)               | OnSelect  |
| btnCheckAvailability (Date Space Screen)            | OnSelect  |
| btnSave&NextApproverScreen (Select Approver Screen) | OnSelect  |
| Building Screen (Building Screen)                   | OnVisible |
| Home Screen (Home Screen)                           | OnVisible |
