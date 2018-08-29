# GETCreditMemoTypewithSuccess

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**integration_id__ns** | **str** | ID of the corresponding object in NetSuite. Only available if you have installed the [Zuora Connector for NetSuite](https://www.zuora.com/connect/app/?appId&#x3D;265).  | [optional] 
**integration_status__ns** | **str** | Status of the credit memo&#39;s synchronization with NetSuite. Only available if you have installed the [Zuora Connector for NetSuite](https://www.zuora.com/connect/app/?appId&#x3D;265).  | [optional] 
**origin__ns** | **str** | Origin of the corresponding object in NetSuite. Only available if you have installed the [Zuora Connector for NetSuite](https://www.zuora.com/connect/app/?appId&#x3D;265).  | [optional] 
**sync_date__ns** | **str** | Date when the credit memo was synchronized with NetSuite. Only available if you have installed the [Zuora Connector for NetSuite](https://www.zuora.com/connect/app/?appId&#x3D;265).  | [optional] 
**transaction__ns** | **str** | Related transaction in NetSuite. Only available if you have installed the [Zuora Connector for NetSuite](https://www.zuora.com/connect/app/?appId&#x3D;265).  | [optional] 
**account_id** | **str** | The ID of the customer account associated with the credit memo.  | [optional] 
**amount** | **float** | The total amount of the credit memo.  | [optional] 
**applied_amount** | **float** | The applied amount of the credit memo.  | [optional] 
**auto_apply_upon_posting** | **bool** | Whether the credit memo automatically applies to the invoice upon posting.  | [optional] 
**cancelled_by_id** | **str** | The ID of the Zuora user who cancelled the credit memo.  | [optional] 
**cancelled_on** | **datetime** | The date and time when the credit memo was cancelled, in &#x60;yyyy-mm-dd hh:mm:ss&#x60; format.  | [optional] 
**comment** | **str** | Comments about the credit memo.  | [optional] 
**created_by_id** | **str** | The ID of the Zuora user who created the credit memo.  | [optional] 
**created_date** | **datetime** | The date and time when the credit memo was created, in &#x60;yyyy-mm-dd hh:mm:ss&#x60; format. For example, 2017-03-01 15:31:10.  | [optional] 
**credit_memo_date** | **date** | The date when the credit memo takes effect, in &#x60;yyyy-mm-dd&#x60; format. For example, 2017-05-20.  | [optional] 
**currency** | **str** | A currency defined in the web-based UI administrative settings.  | [optional] 
**exclude_from_auto_apply_rules** | **bool** | Whether the credit memo is excluded from the rule of automatically applying credit memos to invoices.  | [optional] 
**id** | **str** | The unique ID of the credit memo.  | [optional] 
**latest_pdf_file_id** | **str** | The ID of the latest PDF file generated for the credit memo.  | [optional] 
**number** | **str** | The unique identification number of the credit memo.  | [optional] 
**posted_by_id** | **str** | The ID of the Zuora user who posted the credit memo.  | [optional] 
**posted_on** | **datetime** | The date and time when the credit memo was posted, in &#x60;yyyy-mm-dd hh:mm:ss&#x60; format.  | [optional] 
**reason_code** | **str** | A code identifying the reason for the transaction. The value must be an existing reason code or empty.  | [optional] 
**referred_invoice_id** | **str** | The ID of a referred invoice.  | [optional] 
**refund_amount** | **float** | The amount of the refund on the credit memo.  | [optional] 
**source** | **str** | The source of the credit memo.  Possible values: - &#x60;BillRun&#x60;: The credit memo is generated by a bill run. - &#x60;API&#x60;: The credit memo is created by calling the [Invoice and collect](https://www.zuora.com/developer/api-reference/#operation/POST_TransactionInvoicePayment) operation. - &#x60;ApiSubscribe&#x60;: The credit memo is created by calling the [Create subscription](https://www.zuora.com/developer/api-reference/#operation/POST_Subscription) and [Create account](https://www.zuora.com/developer/api-reference/#operation/POST_Account) operation. - &#x60;ApiAmend&#x60;: The credit memo is created by calling the [Update subscription](https://www.zuora.com/developer/api-reference/#operation/PUT_Subscription) operation. - &#x60;AdhocFromPrpc&#x60;: The credit memo is created from a product rate plan charge through the Zuora UI or by calling the [Create credit memo from charge](https://www.zuora.com/developer/api-reference/#operation/POST_CreditMemoFromPrpc) operation. - &#x60;AdhocFromInvoice&#x60;: The credit memo is created from an invoice or created by reversing an invoice. You can create a credit memo from an invoice through the Zuora UI or by calling the [Create credit memo from invoice](https://www.zuora.com/developer/api-reference/#operation/POST_CreditMemoFromInvoice) operation. You can create a credit memo by reversing an invoice through the Zuora UI or by calling the [Reverse invoice](https://www.zuora.com/developer/api-reference/#operation/PUT_ReverseInvoice) operation.  | [optional] 
**source_id** | **str** | The ID of the credit memo source.   If a credit memo is generated from a bill run, the value is the number of the corresponding bill run. Otherwise, the value is &#x60;null&#x60;.  | [optional] 
**status** | **str** | The status of the credit memo.   | [optional] 
**target_date** | **date** | The target date for the credit memo, in &#x60;yyyy-mm-dd&#x60; format. For example, 2017-07-20.  | [optional] 
**tax_amount** | **float** | The amount of taxation.  | [optional] 
**total_tax_exempt_amount** | **float** | The total amount of taxes or VAT for which the customer has an exemption.  | [optional] 
**transferred_to_accounting** | **str** | Whether the credit memo was transferred to an external accounting system.   | [optional] 
**unapplied_amount** | **float** | The unapplied amount of the credit memo.  | [optional] 
**updated_by_id** | **str** | The ID of the Zuora user who last updated the credit memo.  | [optional] 
**updated_date** | **datetime** | The date and time when the credit memo was last updated, in &#x60;yyyy-mm-dd hh:mm:ss&#x60; format. For example, 2017-03-02 15:36:10.  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

