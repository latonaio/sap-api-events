# sap-api-events
sap-api-events は、[SAP API Business Hub](https://api.sap.com/) に掲載された Event APIs のうち、世界中の企業で繰り返し利用される、利用頻度の高いものをまとめたレポジトリです。  
本レポジトリでまとめられた API のリストに、現時点ではロジスティクス分野しか含められておりませんが、適宜、会計分野等のAPIが追加される予定です。  

## 前提条件  
sap-api-events は、オンプレミス版である（＝クラウド版ではない）SAPS4HANA API の利用を前提としています。  
クラウド版APIを利用する場合は、ご注意ください。  

## 各リソースの所在  
各リソースの所在は、次の箇所です。  

### Central Functions  

* [Business User Events](https://api.sap.com/event/SAPS4HANABusinessEvents_BusinessUserEvents/overview)
* [Classification Events](https://api.sap.com/event/SAPS4HANACloudBusinessEvents_ClassificationClassEvents/overview)
* [Characteristic Events](https://api.sap.com/event/SAPS4HANABusinessEvents_ClassificationCharactersticEvents/overview)
* [Business Partner Events](https://api.sap.com/event/SAPS4HANABusinessEvents_BusinessPartnerEvents/overview)

### Logistics  

* [Product Events](https://api.sap.com/event/SAPS4HANABusinessEvents_ProductEvents/overview)   
* [Batch Events](https://api.sap.com/event/SAPS4HANABusinessEvents_BatchEvents/overview)  

### Inventory Management  

* [Inbound Delivery Events](https://api.sap.com/event/SAPS4HANABusinessEvents_InboundDeliveryEvents/overview)  
* [Material Document Events](https://api.sap.com/event/SAPS4HANABusinessEvents_MaterialDocumentEvents/overview)  

### Sales Management

* [Business Partner Events](https://api.sap.com/event/SAPS4HANABusinessEvents_BusinessPartnerEvents/overview)
* [Customer Material Events](https://api.sap.com/event/SAPS4HANABusinessEvents_CustomerMaterialEvents/overview)
* [Sales Pricing Events](https://api.sap.com/event/SAPS4HANABusinessEvents_SalesPricingConditionRecordEvents/overview)
* [Sales Inquiry Events](https://api.sap.com/event/SAPS4HANABusinessEvents_SalesInquiryEvents/overview)
* [Sales Quotation Events](https://api.sap.com/event/SAPS4HANABusinessEvents_SalesQuotationEvents/overview)
* [Sales Order Events](https://api.sap.com/event/SAPS4HANABusinessEvents_SalesOrderEvents/overview)  
* [Sales Contract Events](https://api.sap.com/event/SAPS4HANABusinessEvents_SalesContractEvents/overview)
* [Sales Scheduling Agreement Events](https://api.sap.com/event/SAPS4HANABusinessEvents_SalesSchedulingAgreementEvents/overview)
* [Outbound Delivery Events](https://api.sap.com/event/SAPS4HANABusinessEvents_OutboundDeliveryEvents/overview)  
* [Customer Return Events](https://api.sap.com/event/SAPS4HANABusinessEvents_CustomerReturnEvents/overview)  
* [Billing Document Events](https://api.sap.com/event/SAPS4HANABusinessEvents_BillingDocumentEvents/overview)  
* [Credit Memo Request Events](https://api.sap.com/event/SAPS4HANACloudBusinessEvents_CreditMemoRequestEvents/overview)
* [Debit Memo Request Events](https://api.sap.com/event/SAPS4HANACloudBusinessEvents_CreditMemoRequestEvents/overview)

### Procurement Management  

* [Business Partner Events](https://api.sap.com/event/SAPS4HANABusinessEvents_BusinessPartnerEvents/overview)
* [Purchasing Info Record Events](https://api.sap.com/event/SAPS4HANABusinessEvents_PurchasingInfoRecord/overview)  
* [Purchase Requisition Events](https://api.sap.com/event/SAPS4HANABusinessEvents_PurchaseRequisitionEvents/overview)  
* [Purchase Order Events](https://api.sap.com/event/SAPS4HANABusinessEvents_PurchaseOrderEvents/overview)  
* [Purchase Contract Events](https://api.sap.com/event/SAPS4HANABusinessEvents_PurchaseContractEvents/overview)
* [Purchase Scheduling Agreement Events](https://api.sap.com/event/SAPS4HANABusinessEvents_PurchaseSchedulingAgreementEvents/overview)
* [Supplier Invoice Events](https://api.sap.com/event/SAPS4HANABusinessEvents_SupplierInvoiceEvents/overview)  

### Production Management  

* [Bill of Material Events](https://api.sap.com/event/SAPS4HANABusinessEvents_BillofMaterialEvents/overview)  
* [Work Center Events](https://api.sap.com/event/SAPS4HANABusinessEvents_WorkCenterEvents/overview)  
* [Production Order Events](https://api.sap.com/event/SAPS4HANABusinessEvents_ProductionOrderEvents/overview)  

### Plant Maintenance  

* [Functional Location Events](https://api.sap.com/event/SAPS4HANACloudBusinessEvents_FunctionalLocationEvents/overview)
* [Equipment Events](https://api.sap.com/event/SAPS4HANABusinessEvents_EquipmentEvents/overview) 
* [Maintenance Bill of Material Events](https://api.sap.com/event/SAPS4HANABusinessEvents_MaintenanceBillOfMaterialEvents/overview) 
* [Maintenance Order Confirmation Events](https://api.sap.com/event/SAPS4HANABusinessEvents_MaintenanceOrderConfirmationEvents/overview)  
* [Measuring Point Events](https://github.com/latonaio/sap-api-integrations-measuring-point-events)
* [Measurement Document Events](https://api.sap.com/event/SAPS4HANACloudBusinessEvents_MeasurementDocumentEvents/overview)

### Customer Service 

* [Service Order Events](https://api.sap.com/event/SAPS4HANABusinessEvents_ServiceOrderEvents/overview)
* [Service Confirmation Events](https://api.sap.com/event/SAPS4HANABusinessEvents_ServiceConfirmationEvents/overview)
